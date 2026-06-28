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
| User AI session hours | 2.9h | 11.1h | 91.9h | 91.9h |
| AI worker hours | 31.9h | 150.3h | 268.3h | 303.8h |
| AI concurrency hours | 37.3h | 167.8h | 425.6h | 462.2h |
| Interactive sessions | 15 | 41 | 185 | 194 |
| Worker sessions | 33 | 125 | 499 | 577 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 30 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 34,214 | 36K | 13.8M | 1,875.1M | $966.55 | $5,062.95 | $3,081.00 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 7,667 | 75K | 2.4M | 547.0M | $340.44 | $1,477.14 | $802.47 |
| deepseek-v4-flash-free | 6,355 | 13.9M | 1.5M | 501.2M | $235.15 | $1,353.48 | $864.47 |
| claude-sonnet-4-5 | 3,287 | 35K | 1.4M | 236.3M | $162.86 | $638.07 | $372.35 |
| claude-haiku-4-5 | 19,392 | 28K | 4.2M | 1,037.9M | $124.99 | $747.31 | $1,779.05 |
| gpt-5.5 | 5,381 | 16.0M | 976K | 251.8M | $122.45 | $680.08 | $553.60 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 13 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| gpt-5.4-mini | 322 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **85,619** | **45.9M** | **26.8M** | **4,986.6M** | **$2,874.60** | **$14,240.23** | **$8,002.81** |

_5,212.5M total tokens processed. 95.7% cache hit rate._

_$22,243.03 total saved ($14,240.23 caching + $8,002.81 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 38,198 | 40K | 15.5M | 2,055.6M | $1,070.91 | $5,550.13 | $3,399.54 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 6,355 | 13.9M | 1.5M | 501.2M | $235.15 | $1,353.48 | $864.47 |
| claude-sonnet-4-5 | 3,287 | 35K | 1.4M | 236.3M | $162.86 | $638.07 | $372.35 |
| claude-haiku-4-5 | 19,392 | 28K | 4.2M | 1,037.9M | $124.99 | $747.31 | $1,779.05 |
| gpt-5.5 | 5,381 | 16.0M | 976K | 251.8M | $122.45 | $680.08 | $553.60 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 13 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| gpt-5.4-mini | 322 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **92,648** | **45.9M** | **29.4M** | **5,392.8M** | **$3,112.46** | **$15,336.94** | **$8,646.71** |

_5,641.8M total tokens processed. 95.6% cache hit rate._

_$23,983.65 total saved ($15,336.94 caching + $8,646.71 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-28 00:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
