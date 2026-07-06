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
| Screen time (Linux) | 11h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 9.6h | 41.8h | 111.5h | 141.6h |
| AI worker hours | 33.4h | 172.5h | 422.7h | 502.5h |
| AI concurrency hours | 47.5h | 247.8h | 612.7h | 749.1h |
| Interactive sessions | 18 | 105 | 253 | 320 |
| Worker sessions | 42 | 176 | 487 | 768 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 34,560 | 36K | 12.9M | 1,870.8M | $948.17 | $5,051.43 | $3,020.15 |
| deepseek-v4-flash-free | 14,234 | 34.4M | 3.3M | 1,135.8M | $536.28 | $3,066.86 | $1,977.76 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 11,115 | 32.5M | 1.9M | 489.7M | $242.10 | $1,322.23 | $1,093.71 |
| claude-haiku-4-5 | 23,311 | 37K | 5.1M | 1,204.5M | $147.49 | $867.31 | $2,073.36 |
| claude-opus-4-6 | 657 | 725 | 268K | 57.2M | $135.96 | $772.93 | $0.00 |
| claude-sonnet-4-0 | 3,048 | 30K | 887K | 191.7M | $123.39 | $517.59 | $283.64 |
| gpt-5.4 | 4,086 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **116,079** | **89.7M** | **32.4M** | **6,380.6M** | **$3,266.97** | **$16,557.00** | **$10,684.10** |

_6,671.9M total tokens processed. 95.6% cache hit rate._

_$27,241.10 total saved ($16,557.00 caching + $10,684.10 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 47,613 | 50K | 18.7M | 2,515.7M | $1,309.97 | $6,792.62 | $4,142.06 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,234 | 34.4M | 3.3M | 1,135.8M | $536.28 | $3,066.86 | $1,977.76 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,343 | 37K | 5.1M | 1,205.6M | $147.64 | $868.05 | $2,075.25 |
| claude-opus-4-6 | 657 | 725 | 268K | 57.2M | $135.96 | $772.93 | $0.00 |
| gpt-5.4 | 4,086 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **139,489** | **93.1M** | **41.2M** | **7,789.8M** | **$4,376.67** | **$21,810.16** | **$12,759.17** |

_8,159.6M total tokens processed. 95.5% cache hit rate._

_$34,569.33 total saved ($21,810.16 caching + $12,759.17 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 12:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
