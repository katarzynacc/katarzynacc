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
| Screen time (Linux) | 8.7h | 63.9h | 126.9h | ~1,351h* |
| User AI session hours | 5.1h | 33.4h | 107.0h | 118.4h |
| AI worker hours | 26.9h | 169.6h | 347.0h | 401.0h |
| AI concurrency hours | 34.6h | 223.2h | 524.7h | 601.8h |
| Interactive sessions | 12 | 108 | 251 | 277 |
| Worker sessions | 14 | 157 | 515 | 663 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 30,828 | 32K | 12.3M | 1,703.1M | $871.77 | $4,598.39 | $2,784.37 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,022 | 25.9M | 2.6M | 878.1M | $413.61 | $2,370.90 | $1,524.16 |
| claude-sonnet-4-0 | 6,816 | 67K | 2.1M | 477.3M | $298.80 | $1,288.87 | $700.77 |
| claude-sonnet-4-5 | 10,864 | 30K | 2.6M | 429.6M | $242.91 | $1,160.03 | $675.23 |
| gpt-5.5 | 10,189 | 30.2M | 1.7M | 455.6M | $224.93 | $1,230.36 | $1,016.39 |
| claude-sonnet-4-5 | 4,408 | 49K | 1.9M | 305.2M | $219.10 | $824.05 | $482.66 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 338 | 395 | 140K | 29.1M | $74.95 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 652 | 4.3M | 58K | 16.7M | $1.88 | $31.43 | $72.37 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **103,712** | **73.1M** | **30.0M** | **5,846.4M** | **$3,234.21** | **$16,133.47** | **$9,605.44** |

_6,119.6M total tokens processed. 95.5% cache hit rate._

_$25,738.91 total saved ($16,133.47 caching + $9,605.44 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,022 | 25.9M | 2.6M | 878.1M | $413.61 | $2,370.90 | $1,524.16 |
| claude-sonnet-4-5 | 10,864 | 30K | 2.6M | 429.6M | $242.91 | $1,160.03 | $675.23 |
| gpt-5.5 | 10,189 | 30.2M | 1.7M | 455.6M | $224.93 | $1,230.36 | $1,016.39 |
| claude-sonnet-4-5 | 4,408 | 49K | 1.9M | 305.2M | $219.10 | $824.05 | $482.66 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 338 | 395 | 140K | 29.1M | $74.95 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 652 | 4.3M | 58K | 16.7M | $1.88 | $31.43 | $72.37 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **115,274** | **73.1M** | **34.5M** | **6,522.1M** | **$3,685.29** | **$18,257.56** | **$10,647.68** |

_6,831.8M total tokens processed. 95.5% cache hit rate._

_$28,905.24 total saved ($18,257.56 caching + $10,647.68 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-02 21:54 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
