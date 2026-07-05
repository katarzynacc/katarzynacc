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
| User AI session hours | 4.6h | 39.1h | 107.1h | 131.9h |
| AI worker hours | 19.8h | 154.1h | 396.7h | 466.5h |
| AI concurrency hours | 26.9h | 226.6h | 580.7h | 698.6h |
| Interactive sessions | 6 | 103 | 244 | 299 |
| Worker sessions | 24 | 158 | 493 | 728 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,828 | 33K | 11.9M | 1,760.2M | $882.93 | $4,752.58 | $2,828.23 |
| claude-opus-4-0 | 2,221 | 21K | 593K | 163.7M | $479.45 | $2,210.14 | $0.00 |
| deepseek-v4-flash-free | 12,725 | 30.4M | 3.0M | 1,015.9M | $478.61 | $2,743.05 | $1,765.28 |
| claude-sonnet-4-5 | 15,940 | 42K | 3.9M | 639.1M | $355.59 | $1,725.75 | $1,004.56 |
| claude-sonnet-4-5 | 4,947 | 56K | 2.2M | 343.1M | $259.34 | $926.39 | $545.23 |
| gpt-5.5 | 11,840 | 34.8M | 2.0M | 525.2M | $259.07 | $1,418.14 | $1,170.59 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-sonnet-4-0 | 3,480 | 34K | 999K | 217.8M | $140.73 | $588.11 | $321.75 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **109,978** | **82.3M** | **30.6M** | **6,066.1M** | **$3,226.44** | **$16,310.24** | **$10,065.62** |

_6,344.5M total tokens processed. 95.6% cache hit rate._

_$26,375.86 total saved ($16,310.24 caching + $10,065.62 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,131 | 46K | 17.4M | 2,357.6M | $1,221.50 | $6,365.54 | $3,875.29 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 12,725 | 30.4M | 3.0M | 1,015.9M | $478.61 | $2,743.05 | $1,765.28 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 15,940 | 42K | 3.9M | 639.1M | $355.59 | $1,725.75 | $1,004.56 |
| claude-sonnet-4-5 | 4,947 | 56K | 2.2M | 343.1M | $259.34 | $926.39 | $545.23 |
| gpt-5.5 | 11,840 | 34.8M | 2.0M | 525.2M | $259.07 | $1,418.14 | $1,170.59 |
| claude-haiku-4-5 | 22,353 | 35K | 4.9M | 1,157.3M | $141.93 | $833.27 | $1,992.95 |
| claude-opus-4-6 | 468 | 527 | 201K | 43.9M | $104.76 | $593.93 | $0.00 |
| gpt-5.4 | 2,738 | 9.4M | 497K | 115.8M | $64.78 | $217.28 | $251.95 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 734 | 4.5M | 67K | 22.2M | $2.14 | $41.74 | $80.49 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **130,388** | **82.4M** | **38.7M** | **7,299.3M** | **$4,118.01** | **$20,511.18** | **$11,918.77** |

_7,645.6M total tokens processed. 95.5% cache hit rate._

_$32,429.94 total saved ($20,511.18 caching + $11,918.77 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-05 10:52 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
