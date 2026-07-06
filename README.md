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
| Screen time (Linux) | 13h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 11.2h | 42.4h | 112.7h | 143.2h |
| AI worker hours | 41.1h | 179.1h | 430.6h | 510.4h |
| AI concurrency hours | 57.6h | 255.2h | 622.3h | 759.4h |
| Interactive sessions | 20 | 104 | 253 | 322 |
| Worker sessions | 43 | 176 | 489 | 770 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 35,443 | 37K | 13.2M | 1,919.0M | $973.05 | $5,181.44 | $3,100.23 |
| deepseek-v4-flash-free | 14,424 | 35.3M | 3.4M | 1,151.9M | $545.10 | $3,110.13 | $2,010.91 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 10,914 | 31.8M | 1.8M | 478.2M | $236.82 | $1,291.28 | $1,069.57 |
| claude-opus-4-6 | 969 | 1K | 405K | 82.1M | $197.19 | $1,109.56 | $0.00 |
| claude-haiku-4-5 | 23,311 | 37K | 5.1M | 1,204.5M | $147.49 | $867.31 | $2,073.36 |
| claude-sonnet-4-0 | 3,009 | 30K | 874K | 188.6M | $121.52 | $509.41 | $279.27 |
| gpt-5.4 | 4,089 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **117,227** | **89.9M** | **32.9M** | **6,455.2M** | **$3,354.75** | **$17,027.77** | **$10,768.81** |

_6,749.1M total tokens processed. 95.6% cache hit rate._

_$27,796.58 total saved ($17,027.77 caching + $10,768.81 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 48,544 | 51K | 19.0M | 2,566.2M | $1,335.97 | $6,928.87 | $4,225.72 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,424 | 35.3M | 3.4M | 1,151.9M | $545.10 | $3,110.13 | $2,010.91 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 969 | 1K | 405K | 82.1M | $197.19 | $1,109.56 | $0.00 |
| claude-haiku-4-5 | 23,343 | 37K | 5.1M | 1,205.6M | $147.64 | $868.05 | $2,075.25 |
| gpt-5.4 | 4,089 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **140,925** | **93.9M** | **41.8M** | **7,881.2M** | **$4,472.72** | **$22,326.30** | **$12,875.97** |

_8,254.6M total tokens processed. 95.5% cache hit rate._

_$35,202.27 total saved ($22,326.30 caching + $12,875.97 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 14:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
