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
| Screen time (Linux) | 12h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 10.8h | 42.1h | 112.4h | 142.8h |
| AI worker hours | 37.8h | 176.7h | 427.3h | 507.1h |
| AI concurrency hours | 53.5h | 252.3h | 618.5h | 755.4h |
| Interactive sessions | 19 | 105 | 252 | 321 |
| Worker sessions | 43 | 178 | 489 | 770 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 35,026 | 36K | 13.1M | 1,897.4M | $961.55 | $5,123.11 | $3,063.95 |
| deepseek-v4-flash-free | 14,313 | 34.7M | 3.3M | 1,141.9M | $539.65 | $3,083.23 | $1,990.57 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 11,115 | 32.5M | 1.9M | 489.7M | $242.10 | $1,322.23 | $1,093.71 |
| claude-opus-4-6 | 950 | 1K | 398K | 81.2M | $193.27 | $1,097.26 | $0.00 |
| claude-haiku-4-5 | 23,311 | 37K | 5.1M | 1,204.5M | $147.49 | $867.31 | $2,073.36 |
| claude-sonnet-4-0 | 3,013 | 30K | 875K | 188.7M | $121.63 | $509.57 | $279.37 |
| gpt-5.4 | 4,087 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **116,883** | **90.0M** | **32.7M** | **6,434.3M** | **$3,339.27** | **$16,961.36** | **$10,736.43** |

_6,727.3M total tokens processed. 95.6% cache hit rate._

_$27,697.79 total saved ($16,961.36 caching + $10,736.43 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 48,079 | 50K | 18.9M | 2,542.3M | $1,323.35 | $6,864.31 | $4,185.86 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,314 | 34.7M | 3.3M | 1,141.9M | $539.67 | $3,083.34 | $1,990.63 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 950 | 1K | 398K | 81.2M | $193.27 | $1,097.26 | $0.00 |
| claude-haiku-4-5 | 23,343 | 37K | 5.1M | 1,205.6M | $147.64 | $868.05 | $2,075.25 |
| gpt-5.4 | 4,087 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **140,329** | **93.4M** | **41.6M** | **7,846.5M** | **$4,450.75** | **$22,222.65** | **$12,815.83** |

_8,218.2M total tokens processed. 95.5% cache hit rate._

_$35,038.47 total saved ($22,222.65 caching + $12,815.83 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 13:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
