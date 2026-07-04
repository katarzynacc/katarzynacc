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
| Screen time (Linux) | 24h | 59.9h | 84.2h | ~1,351h* |
| User AI session hours | 5.7h | 36.6h | 108.7h | 125.7h |
| AI worker hours | 15.3h | 162.8h | 378.6h | 443.5h |
| AI concurrency hours | 35.2h | 232.4h | 566.3h | 666.1h |
| Interactive sessions | 13 | 113 | 249 | 292 |
| Worker sessions | 19 | 154 | 497 | 699 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 36 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 32,509 | 34K | 12.4M | 1,805.8M | $908.17 | $4,875.72 | $2,912.40 |
| claude-opus-4-0 | 2,800 | 26K | 776K | 216.6M | $622.44 | $2,925.02 | $0.00 |
| deepseek-v4-flash-free | 11,827 | 28.7M | 2.8M | 939.9M | $445.48 | $2,537.95 | $1,642.22 |
| claude-sonnet-4-5 | 13,407 | 36K | 3.2M | 541.2M | $301.02 | $1,461.36 | $847.56 |
| claude-sonnet-4-5 | 4,718 | 53K | 2.1M | 327.7M | $244.65 | $884.93 | $521.45 |
| gpt-5.5 | 10,575 | 31.4M | 1.8M | 478.8M | $235.05 | $1,292.94 | $1,062.58 |
| claude-sonnet-4-0 | 5,047 | 50K | 1.5M | 346.8M | $219.05 | $936.40 | $509.82 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **107,880** | **77.2M** | **30.7M** | **6,058.1M** | **$3,346.58** | **$16,860.39** | **$9,926.02** |

_6,337.2M total tokens processed. 95.6% cache hit rate._

_$26,786.41 total saved ($16,860.39 caching + $9,926.02 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 43,179 | 45K | 17.1M | 2,315.5M | $1,198.57 | $6,251.86 | $3,805.95 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| deepseek-v4-flash-free | 11,827 | 28.7M | 2.8M | 939.9M | $445.48 | $2,537.95 | $1,642.22 |
| claude-sonnet-4-5 | 13,407 | 36K | 3.2M | 541.2M | $301.02 | $1,461.36 | $847.56 |
| claude-sonnet-4-5 | 4,718 | 53K | 2.1M | 327.7M | $244.65 | $884.93 | $521.45 |
| gpt-5.5 | 10,575 | 31.4M | 1.8M | 478.8M | $235.05 | $1,292.94 | $1,062.58 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **124,511** | **77.3M** | **37.2M** | **7,021.5M** | **$3,968.67** | **$19,761.34** | **$11,437.58** |

_7,353.5M total tokens processed. 95.5% cache hit rate._

_$31,198.92 total saved ($19,761.34 caching + $11,437.58 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-04 08:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
