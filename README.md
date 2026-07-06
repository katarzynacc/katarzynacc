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
| Screen time (Linux) | 18h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 9.0h | 41.1h | 111.0h | 144.2h |
| AI worker hours | 45.0h | 183.3h | 440.3h | 520.1h |
| AI concurrency hours | 58.6h | 257.4h | 629.1h | 770.8h |
| Interactive sessions | 18 | 91 | 249 | 325 |
| Worker sessions | 46 | 171 | 497 | 778 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 36,428 | 38K | 13.7M | 1,968.0M | $1,000.19 | $5,313.63 | $3,184.68 |
| deepseek-v4-flash-free | 14,694 | 36.3M | 3.4M | 1,174.3M | $556.83 | $3,170.86 | $2,054.15 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,112 | 58K | 2.2M | 354.8M | $267.81 | $958.05 | $562.48 |
| claude-opus-4-0 | 1,185 | 11K | 320K | 84.9M | $259.83 | $1,147.03 | $0.00 |
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
| **Total** | **118,413** | **91.0M** | **33.4M** | **6,502.6M** | **$3,351.53** | **$16,978.04** | **$10,885.15** |

_6,798.2M total tokens processed. 95.7% cache hit rate._

_$27,863.19 total saved ($16,978.04 caching + $10,885.15 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,705 | 52K | 19.5M | 2,622.1M | $1,366.89 | $7,079.77 | $4,321.65 |
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
| **Total** | **142,922** | **96.4M** | **42.6M** | **7,991.9M** | **$4,555.77** | **$22,719.16** | **$13,063.33** |

_8,370.9M total tokens processed. 95.5% cache hit rate._

_$35,782.48 total saved ($22,719.16 caching + $13,063.33 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 19:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
