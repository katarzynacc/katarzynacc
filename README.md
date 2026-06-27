# Kasia CC

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 0h | 89.4h | ~1,132h* |
| User AI session hours | 4.1h | 14.2h | 89.1h | 89.1h |
| AI worker hours | 48.8h | 135.9h | 248.1h | 280.3h |
| AI concurrency hours | 54.7h | 158.5h | 400.3h | 433.3h |
| Interactive sessions | 10 | 41 | 172 | 179 |
| Worker sessions | 45 | 103 | 503 | 551 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 29 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 36,438 | 38K | 14.7M | 1,974.9M | $1,021.97 | $5,332.40 | $3,254.15 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 9,595 | 91K | 2.9M | 679.3M | $421.95 | $1,834.33 | $995.04 |
| deepseek-v4-flash-free | 5,368 | 11.7M | 1.3M | 428.6M | $200.21 | $1,157.36 | $737.79 |
| claude-sonnet-4-5 | 3,287 | 35K | 1.4M | 236.3M | $162.86 | $638.07 | $372.35 |
| gpt-5.5 | 4,877 | 14.4M | 898K | 225.3M | $110.19 | $608.42 | $497.87 |
| claude-haiku-4-5 | 14,205 | 19K | 3.1M | 785.2M | $93.44 | $565.34 | $1,342.09 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **83,079** | **41.8M** | **26.8M** | **4,866.8M** | **$2,931.55** | **$14,417.13** | **$7,744.35** |

_5,093.8M total tokens processed. 95.5% cache hit rate._

_$22,161.48 total saved ($14,417.13 caching + $7,744.35 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 5,368 | 11.7M | 1.3M | 428.6M | $200.21 | $1,157.36 | $737.79 |
| claude-sonnet-4-5 | 3,287 | 35K | 1.4M | 236.3M | $162.86 | $638.07 | $372.35 |
| gpt-5.5 | 4,877 | 14.4M | 898K | 225.3M | $110.19 | $608.42 | $497.87 |
| claude-haiku-4-5 | 14,205 | 19K | 3.1M | 785.2M | $93.44 | $565.34 | $1,342.09 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **85,956** | **41.8M** | **28.0M** | **5,040.9M** | **$3,032.48** | **$14,887.21** | **$8,022.54** |

_5,277.4M total tokens processed. 95.5% cache hit rate._

_$22,909.74 total saved ($14,887.21 caching + $8,022.54 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-27 08:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
