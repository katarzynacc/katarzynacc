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
| Screen time (Linux) | 16h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 10.6h | 41.8h | 111.8h | 143.9h |
| AI worker hours | 46.4h | 184.8h | 439.3h | 519.1h |
| AI concurrency hours | 62.5h | 260.4h | 629.5h | 769.5h |
| Interactive sessions | 22 | 103 | 252 | 325 |
| Worker sessions | 47 | 179 | 497 | 778 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 36,355 | 38K | 13.6M | 1,964.2M | $998.02 | $5,303.58 | $3,178.80 |
| deepseek-v4-flash-free | 14,672 | 36.3M | 3.4M | 1,171.1M | $555.61 | $3,162.05 | $2,049.75 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,210 | 59K | 2.3M | 361.0M | $272.49 | $974.84 | $572.09 |
| gpt-5.5 | 10,705 | 30.5M | 1.8M | 456.3M | $227.08 | $1,232.07 | $1,024.30 |
| claude-opus-4-6 | 1,063 | 1K | 465K | 90.1M | $221.04 | $1,217.37 | $0.00 |
| claude-haiku-4-5 | 23,411 | 37K | 5.1M | 1,209.6M | $148.22 | $870.94 | $2,082.77 |
| claude-sonnet-4-0 | 3,007 | 30K | 873K | 188.5M | $121.09 | $509.14 | $279.07 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **118,678** | **91.0M** | **33.5M** | **6,523.7M** | **$3,412.56** | **$17,275.66** | **$10,883.82** |

_6,820.8M total tokens processed. 95.6% cache hit rate._

_$28,159.48 total saved ($17,275.66 caching + $10,883.82 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,566 | 52K | 19.5M | 2,615.6M | $1,363.38 | $7,062.33 | $4,311.12 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,672 | 36.3M | 3.4M | 1,171.1M | $555.61 | $3,162.05 | $2,049.75 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 1,063 | 1K | 465K | 90.1M | $221.04 | $1,217.37 | $0.00 |
| claude-haiku-4-5 | 23,443 | 37K | 5.1M | 1,210.6M | $148.37 | $871.68 | $2,084.66 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **142,720** | **96.4M** | **42.5M** | **7,978.9M** | **$4,544.87** | **$22,653.02** | **$13,047.73** |

_8,357.5M total tokens processed. 95.5% cache hit rate._

_$35,700.76 total saved ($22,653.02 caching + $13,047.73 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 17:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
