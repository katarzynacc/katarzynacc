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
| Screen time (Linux) | 4.6h | 59.8h | 149.3h | ~1,935h* |
| User AI session hours | 7.1h | 19.9h | 103.9h | 103.9h |
| AI worker hours | 21.2h | 147.4h | 309.7h | 345.2h |
| AI concurrency hours | 32.8h | 180.7h | 486.7h | 523.3h |
| Interactive sessions | 27 | 71 | 227 | 236 |
| Worker sessions | 36 | 144 | 540 | 619 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 32 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,242 | 32K | 12.5M | 1,727.5M | $883.92 | $4,664.29 | $2,824.28 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| claude-sonnet-4-0 | 7,091 | 70K | 2.2M | 498.4M | $311.25 | $1,345.76 | $732.47 |
| deepseek-v4-flash-free | 8,336 | 19.0M | 2.0M | 654.8M | $308.26 | $1,768.17 | $1,135.73 |
| claude-sonnet-4-5 | 4,026 | 44K | 1.7M | 279.8M | $197.87 | $755.55 | $442.16 |
| claude-sonnet-4-5 | 7,345 | 20K | 1.8M | 306.4M | $172.36 | $827.36 | $481.15 |
| gpt-5.5 | 6,402 | 19.4M | 1.1M | 307.4M | $148.71 | $830.02 | $672.88 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-6 | 257 | 302 | 114K | 23.2M | $59.76 | $314.53 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 477 | 3.8M | 38K | 10.0M | $1.43 | $18.77 | $59.18 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **93,771** | **54.8M** | **28.1M** | **5,359.2M** | **$2,969.82** | **$14,759.86** | **$8,697.33** |

_5,605.0M total tokens processed. 95.6% cache hit rate._

_$23,457.20 total saved ($14,759.86 caching + $8,697.33 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 8,336 | 19.0M | 2.0M | 654.8M | $308.26 | $1,768.17 | $1,135.73 |
| claude-sonnet-4-5 | 4,026 | 44K | 1.7M | 279.8M | $197.87 | $755.55 | $442.16 |
| claude-sonnet-4-5 | 7,345 | 20K | 1.8M | 306.4M | $172.36 | $827.36 | $481.15 |
| gpt-5.5 | 6,402 | 19.4M | 1.1M | 307.4M | $148.71 | $830.02 | $672.88 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-6 | 257 | 302 | 114K | 23.2M | $59.76 | $314.53 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 477 | 3.8M | 38K | 10.0M | $1.43 | $18.77 | $59.18 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **104,644** | **54.9M** | **32.3M** | **5,989.4M** | **$3,396.30** | **$16,761.17** | **$9,667.96** |

_6,269.6M total tokens processed. 95.5% cache hit rate._

_$26,429.13 total saved ($16,761.17 caching + $9,667.96 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-30 00:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
