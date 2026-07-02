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
| User AI session hours | 5.3h | 29.9h | 106.3h | 114.6h |
| AI worker hours | 26.8h | 172.1h | 338.8h | 389.8h |
| AI concurrency hours | 34.3h | 221.7h | 518.1h | 585.1h |
| Interactive sessions | 12 | 102 | 250 | 270 |
| Worker sessions | 21 | 154 | 519 | 653 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 34 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,233 | 32K | 12.5M | 1,727.2M | $883.63 | $4,663.71 | $2,823.61 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 10,353 | 24.4M | 2.5M | 817.7M | $386.80 | $2,208.04 | $1,424.96 |
| claude-sonnet-4-0 | 7,091 | 70K | 2.2M | 498.4M | $311.25 | $1,345.76 | $732.47 |
| claude-sonnet-4-5 | 10,087 | 28K | 2.4M | 398.4M | $226.13 | $1,075.72 | $628.21 |
| claude-sonnet-4-5 | 4,408 | 49K | 1.9M | 305.2M | $219.10 | $824.05 | $482.66 |
| gpt-5.5 | 9,268 | 27.9M | 1.6M | 408.6M | $204.50 | $1,103.39 | $923.72 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 338 | 395 | 140K | 29.1M | $74.95 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 613 | 4.2M | 54K | 15.6M | $1.80 | $29.36 | $70.31 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **101,986** | **69.1M** | **29.9M** | **5,752.0M** | **$3,194.42** | **$15,879.46** | **$9,435.44** |

_6,021.6M total tokens processed. 95.5% cache hit rate._

_$25,314.89 total saved ($15,879.46 caching + $9,435.44 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 10,353 | 24.4M | 2.5M | 817.7M | $386.80 | $2,208.04 | $1,424.96 |
| claude-sonnet-4-5 | 10,087 | 28K | 2.4M | 398.4M | $226.13 | $1,075.72 | $628.21 |
| claude-sonnet-4-5 | 4,408 | 49K | 1.9M | 305.2M | $219.10 | $824.05 | $482.66 |
| gpt-5.5 | 9,268 | 27.9M | 1.6M | 408.6M | $204.50 | $1,103.39 | $923.72 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 338 | 395 | 140K | 29.1M | $74.95 | $394.01 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 613 | 4.2M | 54K | 15.6M | $1.80 | $29.36 | $70.31 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **112,868** | **69.2M** | **34.1M** | **6,382.5M** | **$3,621.19** | **$17,881.34** | **$10,406.73** |

_6,686.4M total tokens processed. 95.5% cache hit rate._

_$28,288.07 total saved ($17,881.34 caching + $10,406.73 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-02 10:44 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
