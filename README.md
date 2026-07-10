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
| Screen time (Linux) | 24h | 3.7h | 63.4h | ~1,351h* |
| User AI session hours | 6.7h | 32.7h | 104.6h | 157.8h |
| AI worker hours | 58.2h | 209.2h | 542.8h | 645.7h |
| AI concurrency hours | 68.7h | 261.1h | 724.4h | 919.4h |
| Interactive sessions | 4 | 56 | 239 | 347 |
| Worker sessions | 60 | 203 | 543 | 896 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 43 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 53,344 | 56K | 19.8M | 2,779.3M | $1,439.44 | $7,504.24 | $4,529.54 |
| deepseek-v4-flash-free | 14,267 | 35.9M | 3.2M | 1,152.3M | $542.59 | $3,111.38 | $2,011.08 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,637 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| gpt-5.4 | 6,166 | 22.5M | 1.3M | 291.3M | $160.55 | $546.36 | $625.59 |
| claude-haiku-4-5 | 24,048 | 38K | 5.2M | 1,253.8M | $152.90 | $902.80 | $2,154.42 |
| claude-sonnet-4-0 | 1,534 | 15K | 418K | 97.4M | $61.44 | $263.09 | $142.24 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.6-sol | 203 | 987K | 37K | 10.4M | $11.74 | $28.18 | $26.65 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **134,047** | **97.3M** | **39.2M** | **7,232.8M** | **$3,660.34** | **$18,574.31** | **$12,186.60** |

_7,557.3M total tokens processed. 95.7% cache hit rate._

_$30,760.90 total saved ($18,574.31 caching + $12,186.60 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 69,940 | 74K | 27.0M | 3,595.2M | $1,891.71 | $9,707.29 | $5,936.61 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 16,472 | 41.3M | 3.8M | 1,331.5M | $628.73 | $3,595.25 | $2,326.59 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,366 | 23.1M | 1.4M | 302.4M | $165.59 | $567.12 | $644.61 |
| claude-haiku-4-5 | 24,084 | 38K | 5.2M | 1,254.9M | $153.11 | $903.56 | $2,156.34 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-sol | 203 | 987K | 37K | 10.4M | $11.74 | $28.18 | $26.65 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **169,588** | **110.3M** | **51.7M** | **9,380.2M** | **$5,427.92** | **$27,000.62** | **$15,318.11** |

_9,820.6M total tokens processed. 95.5% cache hit rate._

_$42,318.73 total saved ($27,000.62 caching + $15,318.11 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-10 22:08 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
