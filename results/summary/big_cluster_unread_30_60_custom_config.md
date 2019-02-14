## Loadtest Results
### Score: 135.00 (+101.60, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

### Routes
#### GET /channels/[channel id]/members
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 10834 | 10877 | +43 | +0.40%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 12.92ms | 16.03ms | +3.10ms | +24.01% |
| Median Response Time | 4.00ms | 5.00ms | +1.00ms | +25.00% |
| 95th Percentile | 11.00ms | 13.00ms | +2.00ms | +18.18% |

#### GET /channels/[channel id]/members/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 9944 | 9987 | +43 | +0.43%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 12.86ms | 17.73ms | +4.87ms | +37.88% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 10.00ms | 10.00ms | 0ms | 0% |

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5059 | 5006 | -53 | -1.05%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 15.06ms | 12.25ms | -2.82ms | -18.70% |
| Median Response Time | 6.00ms | 6.00ms | 0ms | 0% |
| 95th Percentile | 14.00ms | 13.00ms | -1.00ms | -7.14% |

#### GET /channels/[channel id]/stats
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 9944 | 9987 | +43 | +0.43%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 6.96ms | 10.71ms | +3.75ms | +53.85% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 8.00ms | 9.00ms | +1.00ms | +12.50% |

#### GET /files/[post id]/thumbnail
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1796 | 326 | -1470 | -81.85%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 30.45ms | 33.61ms | +3.16ms | +10.37% |
| Median Response Time | 16.00ms | 32.00ms | +16.00ms | +100.00% |
| 95th Percentile | 77.00ms | 65.00ms | -12.00ms | -15.58% |

#### GET /plugins/webapp
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1421 | 1418 | -3 | -0.21%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 6.62ms | 4.25ms | -2.38ms | -35.87% |
| Median Response Time | 4.00ms | 5.00ms | +1.00ms | +25.00% |
| 95th Percentile | 7.00ms | 7.50ms | +0.50ms | +7.14% |

#### GET /posts/[post id]/files/info
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2020 | 351 | -1669 | -82.62%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.83ms | 2.20ms | +1.38ms | +166.38% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 2.50ms | +2.50ms | - |

#### GET /teams/[team id]/channels
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 539 | 512 | -27 | -5.01%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 18.32ms | 13.56ms | -4.76ms | -25.99% |
| Median Response Time | 5.00ms | 5.00ms | 0ms | 0% |
| 95th Percentile | 9.00ms | 11.00ms | +2.00ms | +22.22% |

#### GET /teams/[team id]/channels/autocomplete
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1483 | 1268 | -215 | -14.50%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 14.85ms | 17.87ms | +3.02ms | +20.33% |
| Median Response Time | 5.00ms | 6.00ms | +1.00ms | +20.00% |
| 95th Percentile | 8.00ms | 10.50ms | +2.50ms | +31.25% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 4885 | 4981 | +96 | +1.97%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 19.86ms | 19.68ms | -0.18ms | -0.89% |
| Median Response Time | 9.00ms | 10.00ms | +1.00ms | +11.11% |
| 95th Percentile | 20.00ms | 20.00ms | 0ms | 0% |

#### GET /users/email/[email]
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1000 | 1000 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 6.62ms | 6.66ms | +0.04ms | +0.53% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 15.00ms | 12.00ms | -3.00ms | -20.00% |

#### GET /users/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5466 | 5575 | +109 | +1.99%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 26.00ms | 50.66ms | +24.66ms | +94.83% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 13.00ms | 19.50ms | +6.50ms | +50.00% |

#### GET /users/me/teams/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 4086 | 4084 | -2 | -0.05%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 15.51ms | 38.49ms | +22.99ms | +148.26% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 9.00ms | 10.00ms | +1.00ms | +11.11% |

#### POST /channels/members/me/view
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 19888 | 19974 | +86 | +0.43%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 25.95ms | 30.12ms | +4.17ms | +16.05% |
| Median Response Time | 17.00ms | 20.00ms | +3.00ms | +17.65% |
| 95th Percentile | 26.00ms | 27.00ms | +1.00ms | +3.85% |

#### POST /files
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 18 | 15 | -3 | -16.67%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 38.00ms | 390.60ms | +352.60ms | +927.89% |
| Median Response Time | 24.50ms | 54.00ms | +29.50ms | +120.41% |
| 95th Percentile | 75.00ms | 1976.00ms | +1901.00ms | +2534.67% |

#### POST /hooks/incoming
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1207 | 1213 | +6 | +0.50%
| Error Rate | 100.00% | 100.00% | 0% | 0% |
| Mean Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /opengraph
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 37904 | 7587 | -30317 | -79.98%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.66ms | 6.06ms | +0.41ms | +7.19% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 747 | 730 | -17 | -2.28%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 55.23ms | 61.06ms | +5.83ms | +10.56% |
| Median Response Time | 46.00ms | 50.00ms | +4.00ms | +8.70% |
| 95th Percentile | 80.00ms | 76.50ms | -3.50ms | -4.38% |

#### POST /teams/[team id]/channels/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 12809 | 13732 | +923 | +7.21%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 16.52ms | 28.83ms | +12.32ms | +74.55% |
| Median Response Time | 4.00ms | 4.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 7.00ms | 0ms | 0% |

#### POST /teams/[team id]/posts/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 161 | 166 | +5 | +3.11%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 12.30ms | 28.09ms | +15.79ms | +128.30% |
| Median Response Time | 5.00ms | 4.00ms | -1.00ms | -20.00% |
| 95th Percentile | 14.50ms | 12.50ms | -2.00ms | -13.79% |

#### POST /users/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2070 | 2216 | +146 | +7.05%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 7.00ms | 10.65ms | +3.64ms | +52.04% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### POST /users/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1173 | 1183 | +10 | +0.85%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 33.83ms | 31.84ms | -1.99ms | -5.88% |
| Median Response Time | 22.00ms | 24.00ms | +2.00ms | +9.09% |
| 95th Percentile | 28.00ms | 30.00ms | +2.00ms | +7.14% |

#### POST /users/status/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 31879 | 31929 | +50 | +0.16%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 14.30ms | 22.52ms | +8.22ms | +57.53% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 7.00ms | 8.00ms | +1.00ms | +14.29% |

#### POST /users/usernames
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 3763 | 3808 | +45 | +1.20%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 8.58ms | 9.24ms | +0.67ms | +7.79% |
| Median Response Time | 3.00ms | 3.00ms | 0ms | 0% |
| 95th Percentile | 4.00ms | 4.00ms | 0ms | 0% |

#### PUT /users/[user id]/active
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1000 | 1000 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 26.97ms | 36.34ms | +9.37ms | +34.76% |
| Median Response Time | 20.00ms | 27.00ms | +7.00ms | +35.00% |
| 95th Percentile | 50.00ms | 64.00ms | +14.00ms | +28.00% |

