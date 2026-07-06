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
| Screen time (Linux) | 15h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 11.3h | 42.4h | 111.9h | 143.5h |
| AI worker hours | 45.0h | 183.3h | 435.1h | 514.9h |
| AI concurrency hours | 62.0h | 259.7h | 625.8h | 764.8h |
| Interactive sessions | 23 | 106 | 253 | 325 |
| Worker sessions | 47 | 179 | 493 | 774 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 35,843 | 37K | 13.4M | 1,938.6M | $984.18 | $5,234.26 | $3,135.25 |
| deepseek-v4-flash-free | 14,657 | 36.3M | 3.4M | 1,169.9M | $555.13 | $3,158.83 | $2,047.98 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 10,819 | 31.2M | 1.8M | 467.6M | $232.11 | $1,262.57 | $1,047.61 |
| claude-opus-4-6 | 1,027 | 1K | 437K | 87.7M | $208.89 | $1,184.57 | $0.00 |
| claude-haiku-4-5 | 23,364 | 37K | 5.1M | 1,207.5M | $147.84 | $869.41 | $2,078.12 |
| claude-sonnet-4-0 | 3,007 | 30K | 873K | 188.5M | $121.09 | $509.14 | $279.07 |
| gpt-5.4 | 4,387 | 15.8M | 914K | 202.5M | $111.67 | $379.82 | $435.04 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **118,172** | **91.6M** | **33.2M** | **6,504.0M** | **$3,391.38** | **$17,202.67** | **$10,857.52** |

_6,800.3M total tokens processed. 95.6% cache hit rate._

_$28,060.19 total saved ($17,202.67 caching + $10,857.52 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 48,970 | 51K | 19.2M | 2,587.5M | $1,347.82 | $6,986.46 | $4,263.32 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,657 | 36.3M | 3.4M | 1,169.9M | $555.13 | $3,158.83 | $2,047.98 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 1,027 | 1K | 437K | 87.7M | $208.89 | $1,184.57 | $0.00 |
| claude-haiku-4-5 | 23,396 | 37K | 5.1M | 1,208.5M | $148.00 | $870.16 | $2,080.01 |
| gpt-5.4 | 4,387 | 15.8M | 914K | 202.5M | $111.67 | $379.82 | $435.04 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **141,993** | **96.3M** | **42.2M** | **7,942.5M** | **$4,515.22** | **$22,534.95** | **$12,989.42** |

_8,319.3M total tokens processed. 95.5% cache hit rate._

_$35,524.37 total saved ($22,534.95 caching + $12,989.42 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 16:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
