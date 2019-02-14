## Loadtest Results
### Score: 46.80 (+1.42, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

### Routes
#### GET /channels/[channel id]/members
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1808 | 1426 | -382 | -21.13%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.41ms | 3.48ms | +0.06ms | +1.84% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 5.00ms | 5.00ms | 0ms | 0% |

#### GET /channels/[channel id]/members/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1360 | 978 | -382 | -28.09%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.62ms | 1.65ms | +0.03ms | +1.62% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 667 | 978 | +311 | +46.63%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.95ms | 0.94ms | -3.01ms | -76.21% |
| Median Response Time | 3.00ms | 0.00ms | -3.00ms | -100.00% |
| 95th Percentile | 6.00ms | 4.00ms | -2.00ms | -33.33% |

#### GET /channels/[channel id]/stats
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1360 | 978 | -382 | -28.09%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.30ms | 0.40ms | +0.10ms | +35.26% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 3.00ms | 0ms | 0% |

#### GET /files/[post id]/thumbnail
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 135 | 23 | -112 | -82.96%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 39.56ms | 45.57ms | +6.00ms | +15.17% |
| Median Response Time | 34.00ms | 46.00ms | +12.00ms | +35.29% |
| 95th Percentile | 93.00ms | 77.50ms | -15.50ms | -16.67% |

#### GET /plugins/webapp
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 539 | 583 | +44 | +8.16%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.03ms | 0.04ms | +0.01ms | +51.89% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### GET /posts/[post id]/files/info
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 200 | 48 | -152 | -76.00%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.31ms | 0.33ms | +0.02ms | +7.53% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### GET /teams/[team id]/channels
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 76 | 90 | +14 | +18.42%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.28ms | 3.00ms | -0.28ms | -8.43% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 5.00ms | 5.00ms | 0ms | 0% |

#### GET /teams/[team id]/channels/autocomplete
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 140 | 271 | +131 | +93.57%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 4.36ms | 4.46ms | +0.10ms | +2.30% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 6.00ms | 6.00ms | 0ms | 0% |

#### GET /users/email/[email]
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 500 | 500 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 35.24ms | 34.98ms | -0.26ms | -0.73% |
| Median Response Time | 29.00ms | 30.00ms | +1.00ms | +3.45% |
| 95th Percentile | 101.00ms | 101.00ms | 0ms | 0% |

#### GET /users/me/teams/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 584 | 803 | +219 | +37.50%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.04ms | 2.83ms | -0.21ms | -6.75% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### POST /channels/members/me/view
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2720 | 1956 | -764 | -28.09%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 11.30ms | 12.19ms | +0.89ms | +7.87% |
| Median Response Time | 12.00ms | 12.00ms | 0ms | 0% |
| 95th Percentile | 14.00ms | 15.00ms | +1.00ms | +7.14% |

#### POST /files
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1 | 1 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 26.00ms | 75.00ms | +49.00ms | +188.46% |
| Median Response Time | 26.00ms | 75.00ms | +49.00ms | +188.46% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /hooks/incoming
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 169 | 166 | -3 | -1.78%
| Error Rate | 100.00% | 100.00% | 0% | 0% |
| Mean Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /opengraph
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 3958 | 748 | -3210 | -81.10%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.05ms | 0.21ms | +0.16ms | +324.39% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 93 | 127 | +34 | +36.56%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 48.22ms | 45.68ms | -2.54ms | -5.26% |
| Median Response Time | 51.00ms | 40.00ms | -11.00ms | -21.57% |
| 95th Percentile | 74.00ms | 62.50ms | -11.50ms | -15.54% |

#### POST /teams/[team id]/channels/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1851 | 2274 | +423 | +22.85%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.87ms | 2.84ms | -0.03ms | -1.00% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### POST /teams/[team id]/posts/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 23 | 44 | +21 | +91.30%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.87ms | 2.70ms | -0.17ms | -5.75% |
| Median Response Time | 3.00ms | 2.00ms | -1.00ms | -33.33% |
| 95th Percentile | 4.00ms | 5.00ms | +1.00ms | +25.00% |

#### POST /users/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 296 | 210 | -86 | -29.05%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.30ms | 1.26ms | -0.04ms | -3.23% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### POST /users/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 86 | 243 | +157 | +182.56%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 21.14ms | 20.47ms | -0.67ms | -3.15% |
| Median Response Time | 22.00ms | 22.00ms | 0ms | 0% |
| 95th Percentile | 27.50ms | 26.00ms | -1.50ms | -5.45% |

#### POST /users/status/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 14110 | 13781 | -329 | -2.33%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.03ms | 2.07ms | +0.04ms | +2.06% |
| Median Response Time | 2.00ms | 2.00ms | 0ms | 0% |
| 95th Percentile | 3.00ms | 4.00ms | +1.00ms | +33.33% |

#### POST /users/usernames
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 497 | 391 | -106 | -21.33%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 1.31ms | 1.29ms | -0.02ms | -1.48% |
| Median Response Time | 1.00ms | 1.00ms | 0ms | 0% |
| 95th Percentile | 2.00ms | 2.00ms | 0ms | 0% |

#### PUT /users/[user id]/active
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 500 | 500 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 112.65ms | 115.61ms | +2.96ms | +2.63% |
| Median Response Time | 113.00ms | 112.00ms | -1.00ms | -0.88% |
| 95th Percentile | 203.00ms | 202.00ms | -1.00ms | -0.49% |

