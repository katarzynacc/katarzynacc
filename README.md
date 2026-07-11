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
| Screen time (Linux) | 11h | 3.7h | 63.4h | ~1,351h* |
| User AI session hours | 4.9h | 30.4h | 105.8h | 159.0h |
| AI worker hours | 106.0h | 281.6h | 623.8h | 729.4h |
| AI concurrency hours | 115.4h | 331.5h | 808.8h | 1,006.6h |
| Interactive sessions | 10 | 62 | 247 | 355 |
| Worker sessions | 66 | 226 | 558 | 933 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 43 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 60,566 | 64K | 22.5M | 3,165.4M | $1,636.34 | $8,546.63 | $5,150.03 |
| deepseek-v4-flash-free | 14,785 | 36.7M | 3.4M | 1,189.0M | $559.79 | $3,210.54 | $2,072.25 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,624 | 30.3M | 1.8M | 453.1M | $225.73 | $1,223.63 | $1,018.13 |
| gpt-5.4 | 6,724 | 24.7M | 1.5M | 344.2M | $182.56 | $645.53 | $709.14 |
| claude-haiku-4-5 | 24,048 | 38K | 5.2M | 1,253.8M | $152.90 | $902.80 | $2,154.42 |
| gpt-5.6-sol | 952 | 3.4M | 158K | 40.1M | $43.61 | $108.32 | $99.37 |
| claude-sonnet-4-0 | 1,065 | 10K | 289K | 62.1M | $41.37 | $167.76 | $92.03 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **142,612** | **102.8M** | **42.1M** | **7,702.9M** | **$3,908.25** | **$19,799.83** | **$12,974.30** |

_8,044.8M total tokens processed. 95.7% cache hit rate._

_$32,774.13 total saved ($19,799.83 caching + $12,974.30 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 77,511 | 82K | 29.7M | 4,008.4M | $2,100.55 | $10,822.75 | $6,598.93 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 16,990 | 42.2M | 3.9M | 1,368.3M | $645.93 | $3,694.42 | $2,387.75 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,084 | 38K | 5.2M | 1,254.9M | $153.11 | $903.56 | $2,156.34 |
| gpt-5.6-sol | 952 | 3.4M | 158K | 40.1M | $43.61 | $108.32 | $99.37 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **178,984** | **115.8M** | **54.8M** | **9,912.6M** | **$5,707.85** | **$28,394.56** | **$16,197.87** |

_10,373.2M total tokens processed. 95.6% cache hit rate._

_$44,592.43 total saved ($28,394.56 caching + $16,197.87 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-11 13:39 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
