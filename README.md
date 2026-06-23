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
| User AI session hours | 1.9h | 30.0h | 84.0h | 84.0h |
| AI worker hours | 23.6h | 98.9h | 212.0h | 212.0h |
| AI concurrency hours | 25.7h | 150.5h | 356.9h | 356.9h |
| Interactive sessions | 3 | 56 | 165 | 165 |
| Worker sessions | 21 | 85 | 493 | 493 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 25 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 37,305 | 39K | 15.2M | 2,013.1M | $1,049.22 | $5,435.44 | $3,328.80 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 4,330 | 9.5M | 1.1M | 355.6M | $165.62 | $960.12 | $609.50 |
| claude-sonnet-4-5 | 3,287 | 35K | 1.4M | 236.3M | $162.86 | $638.07 | $372.35 |
| gpt-5.5 | 4,360 | 13.1M | 818K | 205.2M | $100.16 | $554.25 | $453.06 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **69,340** | **38.2M** | **24.1M** | **4,121.1M** | **$2,872.96** | **$13,956.52** | **$6,438.53** |

_4,331.4M total tokens processed. 95.1% cache hit rate._

_$20,395.04 total saved ($13,956.52 caching + $6,438.53 model routing vs all-Opus)._

_Model savings are modest because ~95.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 37,305 | 39K | 15.2M | 2,013.1M | $1,049.22 | $5,435.44 | $3,328.80 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 4,330 | 9.5M | 1.1M | 355.6M | $165.62 | $960.12 | $609.50 |
| claude-sonnet-4-5 | 3,287 | 35K | 1.4M | 236.3M | $162.86 | $638.07 | $372.35 |
| gpt-5.5 | 4,360 | 13.1M | 818K | 205.2M | $100.16 | $554.25 | $453.06 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **69,340** | **38.2M** | **24.1M** | **4,121.1M** | **$2,872.96** | **$13,956.52** | **$6,438.53** |

_4,331.4M total tokens processed. 95.1% cache hit rate._

_$20,395.04 total saved ($13,956.52 caching + $6,438.53 model routing vs all-Opus)._

_Model savings are modest because ~95.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-23 05:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
