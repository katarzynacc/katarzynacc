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
| Screen time (Linux) | 20h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 6.9h | 41.6h | 110.3h | 144.7h |
| AI worker hours | 49.9h | 185.7h | 445.4h | 525.1h |
| AI concurrency hours | 62.7h | 261.8h | 634.5h | 778.0h |
| Interactive sessions | 24 | 99 | 256 | 333 |
| Worker sessions | 53 | 178 | 505 | 786 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 39 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 37,517 | 39K | 14.1M | 2,017.7M | $1,027.72 | $5,447.89 | $3,269.32 |
| deepseek-v4-flash-free | 14,709 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,427 | 61K | 2.3M | 369.7M | $278.10 | $998.23 | $585.56 |
| claude-opus-4-0 | 1,133 | 11K | 306K | 79.8M | $243.55 | $1,078.38 | $0.00 |
| claude-opus-4-6 | 1,154 | 1K | 493K | 95.9M | $235.03 | $1,295.61 | $0.00 |
| gpt-5.5 | 10,704 | 30.5M | 1.8M | 456.3M | $227.08 | $1,232.07 | $1,024.30 |
| claude-haiku-4-5 | 23,417 | 37K | 5.1M | 1,210.0M | $148.26 | $871.24 | $2,083.43 |
| claude-sonnet-4-0 | 3,007 | 30K | 873K | 188.5M | $121.09 | $509.14 | $279.07 |
| gpt-5.4 | 4,290 | 15.6M | 896K | 197.8M | $109.53 | $370.99 | $426.94 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **119,707** | **90.8M** | **33.9M** | **6,559.6M** | **$3,378.79** | **$17,113.89** | **$10,984.93** |

_6,858.1M total tokens processed. 95.6% cache hit rate._

_$28,098.81 total saved ($17,113.89 caching + $10,984.93 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,860 | 53K | 20.0M | 2,675.6M | $1,396.21 | $7,224.38 | $4,412.30 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,709 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,548 | 62K | 2.4M | 378.9M | $284.51 | $1,023.06 | $599.62 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 1,154 | 1K | 493K | 95.9M | $235.03 | $1,295.61 | $0.00 |
| claude-haiku-4-5 | 23,449 | 37K | 5.1M | 1,211.0M | $148.41 | $871.98 | $2,085.32 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **144,463** | **96.6M** | **43.1M** | **8,065.1M** | **$4,604.33** | **$22,947.51** | **$13,181.31** |

_8,447.9M total tokens processed. 95.5% cache hit rate._

_$36,128.82 total saved ($22,947.51 caching + $13,181.31 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 21:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
