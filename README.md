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
| Screen time (Linux) | 9.7h | 64.9h | 127.9h | ~1,351h* |
| User AI session hours | 5.1h | 33.9h | 107.0h | 118.9h |
| AI worker hours | 30.5h | 173.8h | 350.8h | 405.3h |
| AI concurrency hours | 38.0h | 228.2h | 528.2h | 607.0h |
| Interactive sessions | 11 | 109 | 252 | 278 |
| Worker sessions | 15 | 158 | 515 | 664 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 35 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 30,641 | 32K | 12.2M | 1,693.5M | $866.32 | $4,572.70 | $2,768.43 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,140 | 26.4M | 2.6M | 885.1M | $417.88 | $2,389.95 | $1,539.96 |
| claude-sonnet-4-0 | 6,582 | 65K | 2.0M | 454.5M | $286.64 | $1,227.41 | $668.71 |
| claude-sonnet-4-5 | 10,911 | 30K | 2.6M | 430.9M | $243.96 | $1,163.58 | $677.56 |
| gpt-5.5 | 10,196 | 30.2M | 1.7M | 455.6M | $224.93 | $1,230.36 | $1,016.39 |
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
| **Total** | **103,463** | **73.5M** | **29.9M** | **5,822.5M** | **$3,221.92** | **$16,068.91** | **$9,575.57** |

_6,094.7M total tokens processed. 95.5% cache hit rate._

_$25,644.48 total saved ($16,068.91 caching + $9,575.57 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,223 | 40K | 15.5M | 2,056.3M | $1,071.59 | $5,552.23 | $3,401.48 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,140 | 26.4M | 2.6M | 885.1M | $417.88 | $2,389.95 | $1,539.96 |
| claude-sonnet-4-5 | 10,911 | 30K | 2.6M | 430.9M | $243.96 | $1,163.58 | $677.56 |
| gpt-5.5 | 10,196 | 30.2M | 1.7M | 455.6M | $224.93 | $1,230.36 | $1,016.39 |
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
| **Total** | **115,471** | **73.6M** | **34.6M** | **6,531.3M** | **$3,691.29** | **$18,282.24** | **$10,667.75** |

_6,841.7M total tokens processed. 95.5% cache hit rate._

_$28,950.00 total saved ($18,282.24 caching + $10,667.75 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-02 22:54 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
