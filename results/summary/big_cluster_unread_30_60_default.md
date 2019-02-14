## Loadtest Results
### Score: 32.16 (-14.10, relative to baseline)
The score is the average of the 95th percentile, median and interquartile ranges in the routes below.

### Routes
#### GET /channels/[channel id]/members
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1807 | 1814 | +7 | +0.39%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 7.85ms | 4.41ms | -3.44ms | -43.82% |
| Median Response Time | 7.00ms | 4.00ms | -3.00ms | -42.86% |
| 95th Percentile | 16.00ms | 8.00ms | -8.00ms | -50.00% |

#### GET /channels/[channel id]/members/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1359 | 1362 | +3 | +0.22%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.20ms | 2.81ms | -2.40ms | -46.06% |
| Median Response Time | 5.00ms | 2.00ms | -3.00ms | -60.00% |
| 95th Percentile | 11.00ms | 6.00ms | -5.00ms | -45.45% |

#### GET /channels/[channel id]/posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 684 | 707 | +23 | +3.36%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 8.28ms | 6.33ms | -1.95ms | -23.50% |
| Median Response Time | 6.00ms | 6.00ms | 0ms | 0% |
| 95th Percentile | 13.00ms | 11.00ms | -2.00ms | -15.38% |

#### GET /channels/[channel id]/stats
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1359 | 1362 | +3 | +0.22%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.81ms | 1.60ms | -1.21ms | -43.06% |
| Median Response Time | 3.00ms | 1.00ms | -2.00ms | -66.67% |
| 95th Percentile | 8.00ms | 5.00ms | -3.00ms | -37.50% |

#### GET /files/[post id]/thumbnail
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 195 | 646 | +451 | +231.28%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 46.90ms | 30.42ms | -16.49ms | -35.15% |
| Median Response Time | 39.00ms | 18.00ms | -21.00ms | -53.85% |
| 95th Percentile | 103.00ms | 75.00ms | -28.00ms | -27.18% |

#### GET /plugins/webapp
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 544 | 551 | +7 | +1.29%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.96ms | 2.20ms | -3.76ms | -63.10% |
| Median Response Time | 5.00ms | 3.00ms | -2.00ms | -40.00% |
| 95th Percentile | 8.00ms | 4.00ms | -4.00ms | -50.00% |

#### GET /posts/[post id]/files/info
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 194 | 601 | +407 | +209.79%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.72ms | 0.03ms | -0.69ms | -95.39% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 6.00ms | 0.00ms | -6.00ms | -100.00% |

#### GET /teams/[team id]/channels
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 64 | 55 | -9 | -14.06%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.70ms | 4.15ms | -1.56ms | -27.31% |
| Median Response Time | 5.00ms | 4.00ms | -1.00ms | -20.00% |
| 95th Percentile | 10.50ms | 6.50ms | -4.00ms | -38.10% |

#### GET /teams/[team id]/channels/autocomplete
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 262 | 73 | -189 | -72.14%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.68ms | 4.67ms | -1.01ms | -17.81% |
| Median Response Time | 5.00ms | 4.00ms | -1.00ms | -20.00% |
| 95th Percentile | 8.00ms | 7.50ms | -0.50ms | -6.25% |

#### GET /users/[user id]/channels/[channel id]/posts/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 675 | 655 | -20 | -2.96%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 12.46ms | 8.51ms | -3.95ms | -31.71% |
| Median Response Time | 9.00ms | 8.00ms | -1.00ms | -11.11% |
| 95th Percentile | 20.00ms | 14.00ms | -6.00ms | -30.00% |

#### GET /users/email/[email]
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 500 | 500 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.73ms | 1.83ms | -3.90ms | -68.04% |
| Median Response Time | 3.00ms | 2.00ms | -1.00ms | -33.33% |
| 95th Percentile | 13.00ms | 4.00ms | -9.00ms | -69.23% |

#### GET /users/me
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 752 | 731 | -21 | -2.79%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 9.71ms | 7.06ms | -2.65ms | -27.27% |
| Median Response Time | 8.00ms | 6.00ms | -2.00ms | -25.00% |
| 95th Percentile | 14.00ms | 11.00ms | -3.00ms | -21.43% |

#### GET /users/me/teams/unread
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 562 | 520 | -42 | -7.47%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 5.38ms | 3.15ms | -2.23ms | -41.51% |
| Median Response Time | 3.00ms | 2.00ms | -1.00ms | -33.33% |
| 95th Percentile | 9.00ms | 6.00ms | -3.00ms | -33.33% |

#### POST /channels/members/me/view
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 2718 | 2724 | +6 | +0.22%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 20.39ms | 14.57ms | -5.82ms | -28.54% |
| Median Response Time | 21.00ms | 14.00ms | -7.00ms | -33.33% |
| 95th Percentile | 27.00ms | 20.00ms | -7.00ms | -25.93% |

#### POST /files
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 5 | 7 | +2 | +40.00%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 99.00ms | 59.43ms | -39.57ms | -39.97% |
| Median Response Time | 82.00ms | 27.00ms | -55.00ms | -67.07% |
| 95th Percentile | 165.00ms | 140.50ms | -24.50ms | -14.85% |

#### POST /hooks/incoming
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 167 | 180 | +13 | +7.78%
| Error Rate | 100.00% | 100.00% | 0% | 0% |
| Mean Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /opengraph
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 3879 | 11177 | +7298 | +188.14%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 0.08ms | 0.02ms | -0.07ms | -81.27% |
| Median Response Time | 0.00ms | 0.00ms | 0ms | 0% |
| 95th Percentile | 0.00ms | 0.00ms | 0ms | 0% |

#### POST /posts
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 101 | 119 | +18 | +17.82%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 61.26ms | 49.85ms | -11.41ms | -18.62% |
| Median Response Time | 63.00ms | 50.00ms | -13.00ms | -20.63% |
| 95th Percentile | 74.00ms | 71.00ms | -3.00ms | -4.05% |

#### POST /teams/[team id]/channels/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 1733 | 1946 | +213 | +12.29%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 4.44ms | 3.05ms | -1.39ms | -31.32% |
| Median Response Time | 4.00ms | 3.00ms | -1.00ms | -25.00% |
| 95th Percentile | 7.00ms | 5.00ms | -2.00ms | -28.57% |

#### POST /teams/[team id]/posts/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 20 | 20 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 6.05ms | 9.55ms | +3.50ms | +57.85% |
| Median Response Time | 4.00ms | 6.00ms | +2.00ms | +50.00% |
| 95th Percentile | 10.00ms | 27.00ms | +17.00ms | +170.00% |

#### POST /users/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 315 | 285 | -30 | -9.52%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 2.98ms | 1.59ms | -1.39ms | -46.74% |
| Median Response Time | 3.00ms | 2.00ms | -1.00ms | -33.33% |
| 95th Percentile | 4.00ms | 2.00ms | -2.00ms | -50.00% |

#### POST /users/search
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 223 | 196 | -27 | -12.11%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 20.34ms | 19.45ms | -0.89ms | -4.38% |
| Median Response Time | 22.00ms | 21.00ms | -1.00ms | -4.55% |
| 95th Percentile | 27.00ms | 23.00ms | -4.00ms | -14.81% |

#### POST /users/status/ids
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 14070 | 14203 | +133 | +0.95%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.98ms | 2.20ms | -1.79ms | -44.83% |
| Median Response Time | 3.00ms | 2.00ms | -1.00ms | -33.33% |
| 95th Percentile | 9.00ms | 5.00ms | -4.00ms | -44.44% |

#### POST /users/usernames
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 531 | 523 | -8 | -1.51%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 3.01ms | 1.66ms | -1.34ms | -44.69% |
| Median Response Time | 3.00ms | 2.00ms | -1.00ms | -33.33% |
| 95th Percentile | 4.00ms | 2.00ms | -2.00ms | -50.00% |

#### PUT /users/[user id]/active
| Metric | Baseline | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- |
| Hits | 500 | 500 | 0 | 0%
| Error Rate | 0.00% | 0.00% | 0% | 0% |
| Mean Response Time | 29.78ms | 16.03ms | -13.75ms | -46.17% |
| Median Response Time | 19.00ms | 15.00ms | -4.00ms | -21.05% |
| 95th Percentile | 49.00ms | 22.00ms | -27.00ms | -55.10% |

