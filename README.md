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
| Screen time (Linux) | 4h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 7.5h | 41.8h | 109.4h | 138.6h |
| AI worker hours | 21.7h | 156.7h | 404.8h | 481.4h |
| AI concurrency hours | 32.7h | 232.4h | 591.6h | 723.5h |
| Interactive sessions | 18 | 107 | 251 | 316 |
| Worker sessions | 27 | 160 | 471 | 743 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 31,997 | 33K | 11.9M | 1,755.7M | $883.35 | $4,740.59 | $2,825.08 |
| deepseek-v4-flash-free | 13,714 | 33.7M | 3.2M | 1,087.4M | $516.40 | $2,936.20 | $1,904.46 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,232 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 11,309 | 33.2M | 1.9M | 498.2M | $246.56 | $1,345.17 | $1,113.99 |
| claude-haiku-4-5 | 23,029 | 36K | 5.0M | 1,191.9M | $146.01 | $858.18 | $2,052.30 |
| claude-sonnet-4-0 | 3,164 | 32K | 920K | 199.7M | $128.85 | $539.40 | $295.35 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 3,524 | 12.2M | 688K | 159.3M | $86.63 | $298.71 | $336.70 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **112,247** | **87.3M** | **31.1M** | **6,177.1M** | **$3,144.28** | **$15,915.82** | **$10,360.51** |

_6,460.5M total tokens processed. 95.6% cache hit rate._

_$26,276.33 total saved ($15,915.82 caching + $10,360.51 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 44,770 | 47K | 17.6M | 2,384.3M | $1,236.99 | $6,437.72 | $3,920.69 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 13,714 | 33.7M | 3.2M | 1,087.4M | $516.40 | $2,936.20 | $1,904.46 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,232 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,061 | 36K | 5.0M | 1,192.9M | $146.16 | $858.92 | $2,054.19 |
| claude-opus-4-6 | 474 | 537 | 204K | 44.0M | $106.07 | $595.22 | $0.00 |
| gpt-5.4 | 3,524 | 12.2M | 688K | 159.3M | $86.63 | $298.71 | $336.70 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **135,067** | **89.9M** | **39.8M** | **7,553.4M** | **$4,235.90** | **$21,080.17** | **$12,377.28** |

_7,913.3M total tokens processed. 95.5% cache hit rate._

_$33,457.45 total saved ($21,080.17 caching + $12,377.28 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 05:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
