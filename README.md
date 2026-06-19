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
| Screen time (Linux) | 24h | 3.5h | 89.4h | ~1,132h* |
| User AI session hours | 5.3h | 21.7h | 72.1h | 72.1h |
| AI worker hours | 6.5h | 42.8h | 143.5h | 143.5h |
| AI concurrency hours | 16.5h | 79.6h | 268.9h | 268.9h |
| Interactive sessions | 7 | 30 | 133 | 133 |
| Worker sessions | 2 | 110 | 448 | 448 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 21 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 21,022 | 22K | 8.8M | 1,044.7M | $573.18 | $2,820.88 | $1,782.08 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 4,200 | 9.0M | 1.1M | 350.0M | $161.68 | $945.24 | $594.74 |
| gpt-5.5 | 4,070 | 12.3M | 757K | 193.6M | $94.13 | $522.78 | $426.16 |
| claude-sonnet-4-5 | 1,407 | 13K | 607K | 113.0M | $70.35 | $305.30 | $172.33 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **50,620** | **36.9M** | **16.7M** | **3,006.0M** | **$2,272.51** | **$10,877.29** | **$4,650.13** |

_3,172.0M total tokens processed. 94.8% cache hit rate._

_$15,527.43 total saved ($10,877.29 caching + $4,650.13 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 21,022 | 22K | 8.8M | 1,044.7M | $573.18 | $2,820.88 | $1,782.08 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 4,200 | 9.0M | 1.1M | 350.0M | $161.68 | $945.24 | $594.74 |
| gpt-5.5 | 4,070 | 12.3M | 757K | 193.6M | $94.13 | $522.78 | $426.16 |
| claude-sonnet-4-5 | 1,407 | 13K | 607K | 113.0M | $70.35 | $305.30 | $172.33 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **50,620** | **36.9M** | **16.7M** | **3,006.0M** | **$2,272.51** | **$10,877.29** | **$4,650.13** |

_3,172.0M total tokens processed. 94.8% cache hit rate._

_$15,527.43 total saved ($10,877.29 caching + $4,650.13 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-19 07:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
