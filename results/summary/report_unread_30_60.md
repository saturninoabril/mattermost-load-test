# Loadtest Results

## Comparison of unread API in small cluster with default/light config between 60 per page (baseline) and 30 per page before/after limits
### Score: 45.38 (-0.49, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 666 | 667 | +1 | +0.15%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.74ms | 3.95ms | +0.21ms | +5.54% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 6.00ms | -1.00ms | -14.29% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 688 | 693 | +5 | +0.73%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.42ms | 5.51ms | +0.08ms | +1.57% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 10.00ms | 10.00ms | 0ms | 0% |

## Comparison of unread API in small cluster with custom/heavy config between 60 per page (baseline) and 30 per page before/after limits
### Score: 45.18 (+1.32, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5106 | 5046 | -60 | -1.18%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.55ms | 3.60ms | +0.05ms | +1.38% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 7.00ms | 0ms | 0% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 4914 | 4966 | +52 | +1.06%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.18ms | 5.17ms | -0.00ms | -0.03% |
| Median Response Time | 5.00ms | 4.00ms | -1.00ms | -20.00% |
| 95th Percentile | 10.00ms | 10.00ms | 0ms | 0% |

## Comparison of unread API in big cluster with default/light config between 60 per page (baseline) and 30 per page before/after limits
### Score: 32.16 (-14.10, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 684 | 707 | +23 | +3.36%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 8.28ms | 6.33ms | -1.95ms | -23.50% |
| Median Response Time | 6.00ms | 6.00ms | 0ms | 0% |
| 95th Percentile | 13.00ms | 11.00ms | -2.00ms | -15.38% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 675 | 655 | -20 | -2.96%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 12.46ms | 8.51ms | -3.95ms | -31.71% |
| Median Response Time | 9.00ms | 8.00ms | -1.00ms | -11.11% |
| 95th Percentile | 20.00ms | 14.00ms | -6.00ms | -30.00% |

## Comparison of unread API in big cluster with custom/heavy config between 60 per page (baseline) and 30 per page before/after limits
### Score: 135.00 (+101.60, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5059 | 5006 | -53 | -1.05%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 15.06ms | 12.25ms | -2.82ms | -18.70% |
| Median Response Time | 6.00ms | 6.00ms | 0ms | 0% |
| 95th Percentile | 14.00ms | 13.00ms | -1.00ms | -7.14% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 4885 | 4981 | +96 | +1.97%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 19.86ms | 19.68ms | -0.18ms | -0.89% |
| Median Response Time | 9.00ms | 10.00ms | +1.00ms | +11.11% |
| 95th Percentile | 20.00ms | 20.00ms | 0ms | 0% |

Notes:
Small cluster:
``--app-count 1 --db-count 1 --loadtest-count 1 --app-type m4.large --db-type db.r4.large``

Big cluster:
``--app-count 4 --db-count 5 --loadtest-count 4 --app-type m4.xlarge --db-type db.r4.xlarge``

Custom config (changes from default):
```
{
    ...
    "LoadtestEnviromentConfig": {
        "NumUsers": 5000,
        "PostTimeRange": 60000,
        ...
    },
    "UserEntitiesConfiguration": {
        "NumActiveEntities": 1000,
        "ActionRateMilliseconds": 60000,
        ...
    },
    ...
}
