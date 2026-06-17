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
| Screen time (Linux) | 6.7h | 10.2h | 96.1h | ~1,241h* |
| User AI session hours | 5.6h | 22.0h | 64.0h | 64.0h |
| AI worker hours | 4.3h | 31.0h | 121.1h | 121.1h |
| AI concurrency hours | 12.8h | 62.5h | 229.3h | 229.3h |
| Interactive sessions | 9 | 28 | 122 | 122 |
| Worker sessions | 19 | 127 | 445 | 445 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 19 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,095 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 20,140 | 21K | 8.4M | 1,006.1M | $551.14 | $2,716.66 | $1,715.21 |
| claude-sonnet-4-0 | 10,698 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 3,653 | 8.0M | 970K | 303.2M | $141.16 | $818.80 | $518.35 |
| gpt-5.4 | 2,459 | 8.8M | 443K | 102.7M | $58.62 | $192.59 | $228.77 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| gpt-5.5 | 1,772 | 6.2M | 336K | 93.3M | $45.54 | $252.06 | $206.86 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-sonnet-4-5 | 121 | 1K | 50K | 9.1M | $6.41 | $24.83 | $14.07 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **45,274** | **29.0M** | **15.2M** | **2,701.0M** | **$2,099.69** | **$10,039.23** | **$4,106.13** |

_2,849.4M total tokens processed. 94.8% cache hit rate._

_$14,145.35 total saved ($10,039.23 caching + $4,106.13 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,095 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 20,140 | 21K | 8.4M | 1,006.1M | $551.14 | $2,716.66 | $1,715.21 |
| claude-sonnet-4-0 | 10,698 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 3,653 | 8.0M | 970K | 303.2M | $141.16 | $818.80 | $518.35 |
| gpt-5.4 | 2,459 | 8.8M | 443K | 102.7M | $58.62 | $192.59 | $228.77 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| gpt-5.5 | 1,772 | 6.2M | 336K | 93.3M | $45.54 | $252.06 | $206.86 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-sonnet-4-5 | 121 | 1K | 50K | 9.1M | $6.41 | $24.83 | $14.07 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **45,274** | **29.0M** | **15.2M** | **2,701.0M** | **$2,099.69** | **$10,039.23** | **$4,106.13** |

_2,849.4M total tokens processed. 94.8% cache hit rate._

_$14,145.35 total saved ($10,039.23 caching + $4,106.13 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-17 15:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
