## Loadtest Results
### Score: 45.18 (+1.32, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

### Routes
#### GET /channels/[channel id]/members
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 10910 | 10902 | -8 | -0.07%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.21ms | 3.15ms | -0.05ms | -1.66% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### GET /channels/[channel id]/members/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 10020 | 10012 | -8 | -0.08%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.48ms | 1.51ms | +0.04ms | +2.40% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5106 | 5046 | -60 | -1.18%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.55ms | 3.60ms | +0.05ms | +1.38% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 7.00ms | 0ms | 0% |

#### GET /channels/[channel id]/stats
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 10020 | 10012 | -8 | -0.08%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.11ms | 0.10ms | -0.00ms | -2.36% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### GET /files/[post id]/thumbnail
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2242 | 1573 | -669 | -29.84%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 19.67ms | 19.68ms | +0.02ms | +0.08% |
| Median Response Time | 14.00ms | 13.00ms | -1.00ms | -7.14% |
| 95th Percentile | 49.00ms | 48.50ms | -0.50ms | -1.02% |

#### GET /plugins/webapp
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1425 | 1386 | -39 | -2.74%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.40ms | 0.08ms | -0.32ms | -80.80% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 1.00ms | +1.00ms | - |

#### GET /posts/[post id]/files/info
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2521 | 1924 | -597 | -23.68%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.02ms | 0.02ms | +0.00ms | +12.31% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### GET /teams/[team id]/channels
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 499 | 518 | +19 | +3.81%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.34ms | 4.27ms | +0.93ms | +27.98% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 5.00ms | 5.00ms | 0ms | 0% |

#### GET /teams/[team id]/channels/autocomplete
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1328 | 1315 | -13 | -0.98%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 4.62ms | 4.64ms | +0.01ms | +0.23% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 7.00ms | 0ms | 0% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 4914 | 4966 | +52 | +1.06%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.18ms | 5.17ms | -0.00ms | -0.03% |
| Median Response Time | 5.00ms | 4.00ms | -1.00ms | -20.00% |
| 95th Percentile | 10.00ms | 10.00ms | 0ms | 0% |

#### GET /users/email/[email]
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1000 | 1000 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 33.17ms | 33.74ms | +0.57ms | +1.73% |
| Median Response Time | 27.00ms | 28.00ms | +1.00ms | +3.70% |
| 95th Percentile | 97.00ms | 91.00ms | -6.00ms | -6.19% |

#### GET /users/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5510 | 5588 | +78 | +1.42%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 9.84ms | 9.18ms | -0.65ms | -6.65% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 7.00ms | 0ms | 0% |

#### GET /users/me/teams/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 4042 | 4132 | +90 | +2.23%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 6.54ms | 4.99ms | -1.55ms | -23.63% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### POST /channels/members/me/view
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 20040 | 20024 | -16 | -0.08%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 11.28ms | 11.19ms | -0.09ms | -0.76% |
| Median Response Time | 12.00ms | 12.00ms | 0ms | 0% |
| 95th Percentile | 15.00ms | 15.00ms | 0ms | 0% |

#### POST /files
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 14 | 15 | +1 | +7.14%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 40.43ms | 49.53ms | +9.10ms | +22.52% |
| Median Response Time | 42.00ms | 43.00ms | +1.00ms | +2.38% |
| 95th Percentile | 63.50ms | 103.50ms | +40.00ms | +62.99% |

#### POST /hooks/incoming
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1210 | 1201 | -9 | -0.74%
| Error Rate | 100.00% | 100.00% | 0% | 0% |
| Mean Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /opengraph
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 49408 | 34729 | -14679 | -29.71%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.04ms | 0.03ms | -0.00ms | -3.51% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 688 | 661 | -27 | -3.92%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 35.57ms | 37.26ms | +1.69ms | +4.75% |
| Median Response Time | 30.00ms | 31.00ms | +1.00ms | +3.33% |
| 95th Percentile | 59.00ms | 58.50ms | -0.50ms | -0.85% |

#### POST /teams/[team id]/channels/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 14100 | 13454 | -646 | -4.58%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.92ms | 2.92ms | -0.00ms | -0.14% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### POST /teams/[team id]/posts/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 177 | 192 | +15 | +8.47%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.66ms | 3.26ms | -0.41ms | -11.08% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 8.50ms | 6.00ms | -2.50ms | -29.41% |

#### POST /users/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2191 | 2274 | +83 | +3.79%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.58ms | 1.53ms | -0.05ms | -3.18% |
| Median Response Time | 2.00ms | 1.00ms | -1.00ms | -50.00% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### POST /users/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1284 | 1112 | -172 | -13.40%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 22.75ms | 23.09ms | +0.35ms | +1.52% |
| Median Response Time | 23.00ms | 23.00ms | 0ms | 0% |
| 95th Percentile | 35.50ms | 36.00ms | +0.50ms | +1.41% |

#### POST /users/status/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 31844 | 31905 | +61 | +0.19%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.76ms | 1.74ms | -0.01ms | -0.81% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### POST /users/usernames
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 3796 | 3856 | +60 | +1.58%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.57ms | 1.55ms | -0.02ms | -1.13% |
| Median Response Time | 2.00ms | 1.00ms | -1.00ms | -50.00% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### PUT /users/[user id]/active
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1000 | 1000 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 114.67ms | 118.43ms | +3.77ms | +3.28% |
| Median Response Time | 115.00ms | 120.00ms | +5.00ms | +4.35% |
| 95th Percentile | 213.00ms | 207.00ms | -6.00ms | -2.82% |

