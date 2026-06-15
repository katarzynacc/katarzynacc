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
| Screen time (Linux) | 7.2h | 28h | 93.1h | ~1,205h* |
| User AI session hours | 1.3h | 29.8h | 93.4h | 93.4h |
| AI worker hours | 0.4h | 17.4h | 65.6h | 65.6h |
| AI concurrency hours | 1.7h | 47.2h | 158.9h | 158.9h |
| Interactive sessions | 1 | 32 | 109 | 109 |
| Worker sessions | 12 | 117 | 398 | 398 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are interactive session time (user attention + AI generation) measured from AI message timestamps._

_AI session 365-day totals cover 18 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,094 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 18,878 | 20K | 7.9M | 924.9M | $511.90 | $2,497.35 | $1,590.14 |
| claude-sonnet-4-0 | 10,673 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 2,205 | 5.4M | 582K | 179.2M | $86.14 | $483.88 | $315.51 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| gpt-5.5 | 1,737 | 6.0M | 332K | 92.7M | $44.91 | $250.50 | $204.04 |
| gpt-5.4 | 954 | 3.1M | 166K | 42.2M | $22.77 | $79.18 | $87.54 |
| gpt-5.5-fast | 325 | 1.3M | 70K | 30.4M | $12.42 | $82.33 | $57.12 |
| claude-sonnet-4-5 | 121 | 1K | 50K | 9.1M | $6.41 | $24.83 | $14.07 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| gpt-5.4-mini | 186 | 2.0M | 10K | 516K | $0.57 | $0.97 | $26.21 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| **Total** | **40,467** | **18.2M** | **13.9M** | **2,393.9M** | **$1,912.55** | **$9,065.99** | **$3,572.95** |

_2,527.3M total tokens processed. 94.7% cache hit rate._

_$12,638.93 total saved ($9,065.99 caching + $3,572.95 model routing vs all-Opus)._

_Model savings are modest because ~94.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-0 | 3,094 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-6 | 18,878 | 20K | 7.9M | 924.9M | $511.90 | $2,497.35 | $1,590.14 |
| claude-sonnet-4-0 | 10,673 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 2,205 | 5.4M | 582K | 179.2M | $86.14 | $483.88 | $315.51 |
| claude-sonnet-4-5 | 2,255 | 6K | 550K | 96.2M | $53.28 | $259.82 | $148.56 |
| gpt-5.5 | 1,737 | 6.0M | 332K | 92.7M | $44.91 | $250.50 | $204.04 |
| gpt-5.4 | 954 | 3.1M | 166K | 42.2M | $22.77 | $79.18 | $87.54 |
| gpt-5.5-fast | 325 | 1.3M | 70K | 30.4M | $12.42 | $82.33 | $57.12 |
| claude-sonnet-4-5 | 121 | 1K | 50K | 9.1M | $6.41 | $24.83 | $14.07 |
| claude-opus-4-7 | 2 | 11 | 12 | 9K | $0.74 | $0.13 | $0.00 |
| gpt-5.4-mini | 186 | 2.0M | 10K | 516K | $0.57 | $0.97 | $26.21 |
| claude-haiku-4-5 | 37 | 52 | 6K | 1.0M | $0.23 | $0.76 | $1.92 |
| **Total** | **40,467** | **18.2M** | **13.9M** | **2,393.9M** | **$1,912.55** | **$9,065.99** | **$3,572.95** |

_2,527.3M total tokens processed. 94.7% cache hit rate._

_$12,638.93 total saved ($9,065.99 caching + $3,572.95 model routing vs all-Opus)._

_Model savings are modest because ~94.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-15 21:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
