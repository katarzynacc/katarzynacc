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
| Screen time (Linux) | 14h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 11.2h | 42.4h | 112.2h | 143.2h |
| AI worker hours | 43.1h | 180.9h | 432.6h | 512.4h |
| AI concurrency hours | 59.7h | 256.9h | 623.6h | 761.6h |
| Interactive sessions | 20 | 104 | 252 | 322 |
| Worker sessions | 45 | 177 | 491 | 772 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 35,739 | 37K | 13.4M | 1,934.5M | $981.74 | $5,223.19 | $3,127.97 |
| deepseek-v4-flash-free | 14,463 | 35.4M | 3.4M | 1,154.9M | $546.71 | $3,118.26 | $2,016.95 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 10,914 | 31.8M | 1.8M | 478.2M | $236.82 | $1,291.28 | $1,069.57 |
| claude-opus-4-6 | 1,027 | 1K | 437K | 87.7M | $208.89 | $1,184.57 | $0.00 |
| claude-haiku-4-5 | 23,311 | 37K | 5.1M | 1,204.5M | $147.49 | $867.31 | $2,073.36 |
| claude-sonnet-4-0 | 3,009 | 30K | 874K | 188.6M | $121.52 | $509.41 | $279.27 |
| gpt-5.4 | 4,089 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **117,620** | **90.0M** | **33.1M** | **6,479.3M** | **$3,376.75** | **$17,152.67** | **$10,802.58** |

_6,773.9M total tokens processed. 95.7% cache hit rate._

_$27,955.25 total saved ($17,152.67 caching + $10,802.58 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 48,866 | 51K | 19.2M | 2,583.4M | $1,345.38 | $6,975.40 | $4,256.04 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,463 | 35.4M | 3.4M | 1,154.9M | $546.71 | $3,118.26 | $2,016.95 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 1,027 | 1K | 437K | 87.7M | $208.89 | $1,184.57 | $0.00 |
| claude-haiku-4-5 | 23,343 | 37K | 5.1M | 1,205.6M | $147.64 | $868.05 | $2,075.25 |
| gpt-5.4 | 4,089 | 14.5M | 833K | 189.1M | $103.11 | $354.58 | $401.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **141,344** | **94.1M** | **42.0M** | **7,907.0M** | **$4,495.44** | **$22,455.97** | **$12,912.33** |

_8,281.2M total tokens processed. 95.5% cache hit rate._

_$35,368.30 total saved ($22,455.97 caching + $12,912.33 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 15:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
