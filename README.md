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
| User AI session hours | 5.1h | 38.5h | 110.7h | 130.2h |
| AI worker hours | 19.0h | 153.6h | 384.6h | 453.0h |
| AI concurrency hours | 27.0h | 225.7h | 573.7h | 682.8h |
| Interactive sessions | 6 | 109 | 246 | 297 |
| Worker sessions | 21 | 146 | 492 | 712 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 32,489 | 34K | 12.2M | 1,793.4M | $901.95 | $4,842.25 | $2,887.33 |
| claude-opus-4-0 | 2,391 | 23K | 629K | 177.6M | $516.33 | $2,398.22 | $0.00 |
| deepseek-v4-flash-free | 12,725 | 30.4M | 3.0M | 1,015.9M | $478.61 | $2,743.05 | $1,765.28 |
| claude-sonnet-4-5 | 14,629 | 39K | 3.6M | 589.5M | $328.00 | $1,591.83 | $924.41 |
| claude-sonnet-4-5 | 4,767 | 54K | 2.1M | 331.2M | $248.18 | $894.34 | $526.95 |
| gpt-5.5 | 10,709 | 31.7M | 1.8M | 482.7M | $237.07 | $1,303.30 | $1,071.59 |
| claude-sonnet-4-0 | 3,933 | 38K | 1.1M | 259.0M | $163.95 | $699.42 | $379.42 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **108,640** | **79.2M** | **30.5M** | **6,050.5M** | **$3,244.81** | **$16,418.49** | **$9,984.96** |

_6,326.2M total tokens processed. 95.6% cache hit rate._

_$26,403.45 total saved ($16,418.49 caching + $9,984.96 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,131 | 46K | 17.4M | 2,357.6M | $1,221.50 | $6,365.54 | $3,875.29 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 12,725 | 30.4M | 3.0M | 1,015.9M | $478.61 | $2,743.05 | $1,765.28 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 14,629 | 39K | 3.6M | 589.5M | $328.00 | $1,591.83 | $924.41 |
| claude-sonnet-4-5 | 4,767 | 54K | 2.1M | 331.2M | $248.18 | $894.34 | $526.95 |
| gpt-5.5 | 10,709 | 31.7M | 1.8M | 482.7M | $237.07 | $1,303.30 | $1,071.59 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **127,766** | **79.3M** | **38.1M** | **7,195.3M** | **$4,057.26** | **$20,230.37** | **$11,721.34** |

_7,534.3M total tokens processed. 95.5% cache hit rate._

_$31,951.70 total saved ($20,230.37 caching + $11,721.34 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-04 21:19 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
