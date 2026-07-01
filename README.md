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
| Screen time (Linux) | 24h | 55.2h | 141.8h | ~1,825h* |
| User AI session hours | 5.1h | 27.0h | 107.2h | 111.7h |
| AI worker hours | 15.7h | 147.3h | 322.3h | 365.0h |
| AI concurrency hours | 24.4h | 192.8h | 503.2h | 556.2h |
| Interactive sessions | 17 | 95 | 245 | 263 |
| Worker sessions | 17 | 139 | 537 | 638 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 33 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,233 | 32K | 12.5M | 1,727.2M | $883.63 | $4,663.71 | $2,823.61 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 10,003 | 23.1M | 2.4M | 791.4M | $372.42 | $2,136.85 | $1,371.68 |
| claude-sonnet-4-0 | 7,091 | 70K | 2.2M | 498.4M | $311.25 | $1,345.76 | $732.47 |
| claude-sonnet-4-5 | 4,294 | 47K | 1.8M | 296.2M | $210.49 | $799.82 | $467.87 |
| claude-sonnet-4-5 | 9,157 | 25K | 2.2M | 369.9M | $208.99 | $998.80 | $582.13 |
| gpt-5.5 | 7,860 | 23.6M | 1.4M | 355.6M | $175.93 | $960.14 | $794.58 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 337 | 392 | 140K | 29.1M | $74.69 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 561 | 4.1M | 48K | 12.3M | $1.64 | $23.20 | $65.63 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **99,131** | **63.4M** | **29.3M** | **5,631.8M** | **$3,125.30** | **$15,557.72** | **$9,187.46** |

_5,892.2M total tokens processed. 95.6% cache hit rate._

_$24,745.18 total saved ($15,557.72 caching + $9,187.46 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 10,003 | 23.1M | 2.4M | 791.4M | $372.42 | $2,136.85 | $1,371.68 |
| claude-sonnet-4-5 | 4,294 | 47K | 1.8M | 296.2M | $210.49 | $799.82 | $467.87 |
| claude-sonnet-4-5 | 9,157 | 25K | 2.2M | 369.9M | $208.99 | $998.80 | $582.13 |
| gpt-5.5 | 7,860 | 23.6M | 1.4M | 355.6M | $175.93 | $960.14 | $794.58 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 337 | 392 | 140K | 29.1M | $74.69 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 561 | 4.1M | 48K | 12.3M | $1.64 | $23.20 | $65.63 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **110,013** | **63.4M** | **33.5M** | **6,262.3M** | **$3,552.07** | **$17,559.60** | **$10,158.76** |

_6,557.1M total tokens processed. 95.5% cache hit rate._

_$27,718.35 total saved ($17,559.60 caching + $10,158.76 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-01 17:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
