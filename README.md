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
| User AI session hours | 5.9h | 28.1h | 107.3h | 112.8h |
| AI worker hours | 16.1h | 153.3h | 328.1h | 371.0h |
| AI concurrency hours | 26.1h | 200.3h | 509.6h | 563.6h |
| Interactive sessions | 19 | 97 | 247 | 265 |
| Worker sessions | 22 | 148 | 545 | 647 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 33 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,233 | 32K | 12.5M | 1,727.2M | $883.63 | $4,663.71 | $2,823.61 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 10,189 | 23.8M | 2.4M | 807.6M | $380.89 | $2,180.61 | $1,402.89 |
| claude-sonnet-4-0 | 7,091 | 70K | 2.2M | 498.4M | $311.25 | $1,345.76 | $732.47 |
| claude-sonnet-4-5 | 9,498 | 26K | 2.3M | 379.1M | $214.72 | $1,023.82 | $597.26 |
| claude-sonnet-4-5 | 4,294 | 47K | 1.8M | 296.2M | $210.49 | $799.82 | $467.87 |
| gpt-5.5 | 8,683 | 25.9M | 1.5M | 382.6M | $191.04 | $1,033.09 | $862.21 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 337 | 392 | 140K | 29.1M | $74.69 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 561 | 4.1M | 48K | 12.3M | $1.64 | $23.20 | $65.63 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **100,481** | **66.4M** | **29.5M** | **5,684.3M** | **$3,154.61** | **$15,699.44** | **$9,301.43** |

_5,948.5M total tokens processed. 95.6% cache hit rate._

_$25,000.88 total saved ($15,699.44 caching + $9,301.43 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 10,189 | 23.8M | 2.4M | 807.6M | $380.89 | $2,180.61 | $1,402.89 |
| claude-sonnet-4-5 | 9,498 | 26K | 2.3M | 379.1M | $214.72 | $1,023.82 | $597.26 |
| claude-sonnet-4-5 | 4,294 | 47K | 1.8M | 296.2M | $210.49 | $799.82 | $467.87 |
| gpt-5.5 | 8,683 | 25.9M | 1.5M | 382.6M | $191.04 | $1,033.09 | $862.21 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 337 | 392 | 140K | 29.1M | $74.69 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 561 | 4.1M | 48K | 12.3M | $1.64 | $23.20 | $65.63 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **111,363** | **66.5M** | **33.7M** | **6,314.8M** | **$3,581.38** | **$17,701.33** | **$10,272.73** |

_6,613.4M total tokens processed. 95.5% cache hit rate._

_$27,974.06 total saved ($17,701.33 caching + $10,272.73 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-01 20:27 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
