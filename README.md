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
| User AI session hours | 4.9h | 21.8h | 72.2h | 72.2h |
| AI worker hours | 7.1h | 43.4h | 144.1h | 144.1h |
| AI concurrency hours | 16.3h | 80.4h | 269.7h | 269.7h |
| Interactive sessions | 6 | 30 | 133 | 133 |
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
| gpt-5.5 | 4,271 | 12.8M | 797K | 201.6M | $98.21 | $544.46 | $444.28 |
| claude-sonnet-4-5 | 1,425 | 13K | 614K | 113.8M | $70.87 | $307.34 | $173.61 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **50,839** | **37.4M** | **16.7M** | **3,014.8M** | **$2,277.11** | **$10,901.01** | **$4,669.54** |

_3,181.4M total tokens processed. 94.8% cache hit rate._

_$15,570.55 total saved ($10,901.01 caching + $4,669.54 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 21,022 | 22K | 8.8M | 1,044.7M | $573.18 | $2,820.88 | $1,782.08 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 4,200 | 9.0M | 1.1M | 350.0M | $161.68 | $945.24 | $594.74 |
| gpt-5.5 | 4,271 | 12.8M | 797K | 201.6M | $98.21 | $544.46 | $444.28 |
| claude-sonnet-4-5 | 1,425 | 13K | 614K | 113.8M | $70.87 | $307.34 | $173.61 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| claude-opus-4-6 | 209 | 252 | 81K | 17.9M | $46.78 | $242.97 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 321 | 3.4M | 17K | 923K | $0.97 | $1.73 | $44.76 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **50,839** | **37.4M** | **16.7M** | **3,014.8M** | **$2,277.11** | **$10,901.01** | **$4,669.54** |

_3,181.4M total tokens processed. 94.8% cache hit rate._

_$15,570.55 total saved ($10,901.01 caching + $4,669.54 model routing vs all-Opus)._

_Model savings are modest because ~94.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-19 08:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
