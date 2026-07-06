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
| Screen time (Linux) | 17h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 10.1h | 41.5h | 111.6h | 144.2h |
| AI worker hours | 45.1h | 182.7h | 439.8h | 519.5h |
| AI concurrency hours | 60.1h | 257.7h | 629.5h | 770.3h |
| Interactive sessions | 19 | 96 | 250 | 325 |
| Worker sessions | 46 | 171 | 497 | 778 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 36,304 | 38K | 13.6M | 1,962.3M | $996.97 | $5,298.27 | $3,175.23 |
| deepseek-v4-flash-free | 14,694 | 36.3M | 3.4M | 1,174.3M | $556.83 | $3,170.86 | $2,054.15 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,412 | 13K | 374K | 106.1M | $312.10 | $1,432.37 | $0.00 |
| claude-sonnet-4-5 | 5,112 | 58K | 2.2M | 354.8M | $267.81 | $958.05 | $562.48 |
| claude-opus-4-6 | 1,098 | 1K | 477K | 93.1M | $227.17 | $1,256.95 | $0.00 |
| gpt-5.5 | 10,704 | 30.5M | 1.8M | 456.3M | $227.08 | $1,232.07 | $1,024.30 |
| claude-haiku-4-5 | 23,417 | 37K | 5.1M | 1,210.0M | $148.26 | $871.24 | $2,083.43 |
| claude-sonnet-4-0 | 3,007 | 30K | 873K | 188.5M | $121.09 | $509.14 | $279.07 |
| gpt-5.4 | 4,419 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **118,516** | **91.0M** | **33.4M** | **6,518.1M** | **$3,400.58** | **$17,248.02** | **$10,875.70** |

_6,814.3M total tokens processed. 95.7% cache hit rate._

_$28,123.72 total saved ($17,248.02 caching + $10,875.70 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,581 | 52K | 19.5M | 2,616.4M | $1,363.67 | $7,064.41 | $4,312.20 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,694 | 36.3M | 3.4M | 1,174.3M | $556.83 | $3,170.86 | $2,054.15 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 1,098 | 1K | 477K | 93.1M | $227.17 | $1,256.95 | $0.00 |
| claude-haiku-4-5 | 23,449 | 37K | 5.1M | 1,211.0M | $148.41 | $871.98 | $2,085.32 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **142,798** | **96.4M** | **42.5M** | **7,986.2M** | **$4,552.55** | **$22,703.79** | **$13,053.88** |

_8,365.0M total tokens processed. 95.5% cache hit rate._

_$35,757.67 total saved ($22,703.79 caching + $13,053.88 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 18:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
