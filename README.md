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
| Screen time (Linux) | 19h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 7.7h | 41.4h | 110.7h | 144.5h |
| AI worker hours | 47.0h | 185.4h | 442.4h | 522.2h |
| AI concurrency hours | 59.9h | 260.5h | 631.6h | 774.0h |
| Interactive sessions | 23 | 97 | 255 | 331 |
| Worker sessions | 48 | 174 | 500 | 781 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 36,924 | 38K | 13.9M | 1,992.1M | $1,013.31 | $5,378.81 | $3,225.88 |
| deepseek-v4-flash-free | 14,709 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,281 | 59K | 2.3M | 360.3M | $271.75 | $972.94 | $571.91 |
| claude-opus-4-0 | 1,185 | 11K | 320K | 84.9M | $259.83 | $1,147.03 | $0.00 |
| claude-opus-4-6 | 1,106 | 1K | 479K | 93.2M | $228.20 | $1,259.25 | $0.00 |
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
| **Total** | **119,101** | **91.2M** | **33.7M** | **6,534.3M** | **$3,370.71** | **$17,065.30** | **$10,940.04** |

_6,831.5M total tokens processed. 95.6% cache hit rate._

_$28,005.35 total saved ($17,065.30 caching + $10,940.04 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,201 | 53K | 19.7M | 2,646.2M | $1,380.01 | $7,144.94 | $4,362.86 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,709 | 36.5M | 3.4M | 1,176.2M | $557.92 | $3,175.75 | $2,058.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,402 | 61K | 2.3M | 369.5M | $278.16 | $997.77 | $585.98 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-opus-4-6 | 1,106 | 1K | 479K | 93.2M | $228.20 | $1,259.25 | $0.00 |
| claude-haiku-4-5 | 23,449 | 37K | 5.1M | 1,211.0M | $148.41 | $871.98 | $2,085.32 |
| gpt-5.4 | 4,420 | 15.9M | 920K | 205.0M | $112.76 | $384.49 | $439.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **143,610** | **96.6M** | **42.8M** | **8,023.6M** | **$4,574.95** | **$22,806.42** | **$13,118.22** |

_8,404.3M total tokens processed. 95.5% cache hit rate._

_$35,924.64 total saved ($22,806.42 caching + $13,118.22 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 20:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
