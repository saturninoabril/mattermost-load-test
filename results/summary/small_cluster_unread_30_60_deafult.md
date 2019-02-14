## Loadtest Results
### Score: 45.38 (-0.49, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

### Routes
#### GET /channels/[channel id]/members
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1802 | 1808 | +6 | +0.33%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.37ms | 3.41ms | +0.04ms | +1.21% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 5.00ms | 5.00ms | 0ms | 0% |

#### GET /channels/[channel id]/members/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1354 | 1360 | +6 | +0.44%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.63ms | 1.62ms | -0.01ms | -0.44% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 666 | 667 | +1 | +0.15%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.74ms | 3.95ms | +0.21ms | +5.54% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 6.00ms | -1.00ms | -14.29% |

#### GET /channels/[channel id]/stats
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1354 | 1360 | +6 | +0.44%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.31ms | 0.30ms | -0.01ms | -4.47% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### GET /files/[post id]/thumbnail
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 254 | 135 | -119 | -46.85%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 36.25ms | 39.56ms | +3.31ms | +9.13% |
| Median Response Time | 31.00ms | 34.00ms | +3.00ms | +9.68% |
| 95th Percentile | 90.50ms | 93.00ms | +2.50ms | +2.76% |

#### GET /plugins/webapp
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 550 | 539 | -11 | -2.00%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.03ms | 0.03ms | -0.01ms | -24.81% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### GET /posts/[post id]/files/info
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 322 | 200 | -122 | -37.89%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.02ms | 0.31ms | +0.29ms | +1147.75% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 2.00ms | +2.00ms | - |

#### GET /teams/[team id]/channels
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 72 | 76 | +4 | +5.56%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.22ms | 3.28ms | +0.05ms | +1.68% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 5.00ms | +1.00ms | +25.00% |

#### GET /teams/[team id]/channels/autocomplete
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 178 | 140 | -38 | -21.35%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 4.44ms | 4.36ms | -0.09ms | -1.95% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 6.00ms | 6.00ms | 0ms | 0% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 688 | 693 | +5 | +0.73%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.42ms | 5.51ms | +0.08ms | +1.57% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 10.00ms | 10.00ms | 0ms | 0% |

#### GET /users/email/[email]
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 500 | 500 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 36.11ms | 35.24ms | -0.88ms | -2.43% |
| Median Response Time | 29.00ms | 29.00ms | 0ms | 0% |
| 95th Percentile | 102.00ms | 101.00ms | -1.00ms | -0.98% |

#### GET /users/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 763 | 767 | +4 | +0.52%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 8.55ms | 6.05ms | -2.50ms | -29.27% |
| Median Response Time | 5.00ms | 5.00ms | 0ms | 0% |
| 95th Percentile | 8.00ms | 8.00ms | 0ms | 0% |

#### GET /users/me/teams/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 549 | 584 | +35 | +6.38%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.18ms | 3.04ms | +0.86ms | +39.17% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### POST /channels/members/me/view
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2708 | 2720 | +12 | +0.44%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 11.29ms | 11.30ms | +0.02ms | +0.14% |
| Median Response Time | 12.00ms | 12.00ms | 0ms | 0% |
| 95th Percentile | 14.00ms | 14.00ms | 0ms | 0% |

#### POST /files
| Metric | Baseline | Actual | Delta |
| --- | --- | --- | --- |
| Hits | - | 1 | - |
| Error Rate | - | 0.00% | - |
| Mean Response Time | - | 26.00ms | - |
| Median Response Time | - | 26.00ms | - |
| 95th Percentile | - | 0.00ms | - |

#### POST /hooks/incoming
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 163 | 169 | +6 | +3.68%
| Error Rate | 100.00% | 100.00% | 0% | 0% |
| Mean Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /opengraph
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5662 | 3958 | -1704 | -30.10%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.04ms | 0.05ms | +0.01ms | +20.43% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 90 | 93 | +3 | +3.33%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 48.30ms | 48.22ms | -0.08ms | -0.18% |
| Median Response Time | 51.00ms | 51.00ms | 0ms | 0% |
| 95th Percentile | 72.50ms | 74.00ms | +1.50ms | +2.07% |

#### POST /teams/[team id]/channels/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2206 | 1851 | -355 | -16.09%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.86ms | 2.87ms | +0.01ms | +0.21% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### POST /teams/[team id]/posts/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 36 | 23 | -13 | -36.11%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.61ms | 2.87ms | -0.74ms | -20.54% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 8.00ms | 4.00ms | -4.00ms | -50.00% |

#### POST /users/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 297 | 296 | -1 | -0.34%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.40ms | 1.30ms | -0.09ms | -6.67% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### POST /users/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 119 | 86 | -33 | -27.73%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 21.70ms | 21.14ms | -0.56ms | -2.57% |
| Median Response Time | 22.00ms | 22.00ms | 0ms | 0% |
| 95th Percentile | 30.50ms | 27.50ms | -3.00ms | -9.84% |

#### POST /users/status/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 14082 | 14110 | +28 | +0.20%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.05ms | 2.03ms | -0.02ms | -0.82% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 3.00ms | -1.00ms | -25.00% |

#### POST /users/usernames
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 499 | 497 | -2 | -0.40%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.37ms | 1.31ms | -0.06ms | -4.60% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### PUT /users/[user id]/active
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 500 | 500 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 112.16ms | 112.65ms | +0.49ms | +0.44% |
| Median Response Time | 111.00ms | 113.00ms | +2.00ms | +1.80% |
| 95th Percentile | 205.00ms | 203.00ms | -2.00ms | -0.98% |