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
| User AI session hours | 2.4h | 30.6h | 101.8h | 152.3h |
| AI worker hours | 40.2h | 190.5h | 518.9h | 619.8h |
| AI concurrency hours | 44.4h | 250.8h | 695.9h | 885.5h |
| Interactive sessions | 2 | 60 | 241 | 345 |
| Worker sessions | 37 | 184 | 528 | 867 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,680 | 52K | 18.5M | 2,558.7M | $1,330.34 | $6,908.56 | $4,181.63 |
| deepseek-v4-flash-free | 13,636 | 34.8M | 3.1M | 1,089.3M | $517.11 | $2,941.28 | $1,914.97 |
| claude-opus-4-6 | 1,906 | 2K | 773K | 137.3M | $352.33 | $1,853.66 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-haiku-4-5 | 23,867 | 37K | 5.2M | 1,241.4M | $151.54 | $893.88 | $2,133.63 |
| gpt-5.4 | 5,650 | 20.2M | 1.2M | 260.6M | $143.54 | $488.67 | $559.11 |
| claude-sonnet-4-0 | 1,549 | 15K | 421K | 97.7M | $61.84 | $263.88 | $142.76 |
| claude-opus-4-0 | 119 | 1K | 41K | 8.2M | $27.31 | $111.72 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,131 | 5.4M | 131K | 43.0M | $3.24 | $80.68 | $114.56 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **128,501** | **92.6M** | **37.3M** | **6,877.9M** | **$3,463.71** | **$17,527.93** | **$11,619.65** |

_7,189.5M total tokens processed. 95.7% cache hit rate._

_$29,147.58 total saved ($17,527.93 caching + $11,619.65 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 65,886 | 69K | 25.4M | 3,357.5M | $1,772.84 | $9,065.39 | $5,559.53 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 15,722 | 39.9M | 3.7M | 1,259.8M | $598.53 | $3,401.67 | $2,213.04 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,906 | 2K | 773K | 137.3M | $352.33 | $1,853.66 | $0.00 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,903 | 37K | 5.2M | 1,242.5M | $151.75 | $894.63 | $2,135.55 |
| gpt-5.4 | 5,847 | 20.7M | 1.2M | 271.6M | $148.58 | $509.42 | $578.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,131 | 5.4M | 131K | 43.0M | $3.24 | $80.68 | $114.56 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **163,390** | **105.2M** | **49.6M** | **8,990.9M** | **$5,189.09** | **$25,772.03** | **$14,704.03** |

_9,416.5M total tokens processed. 95.5% cache hit rate._

_$40,476.06 total saved ($25,772.03 caching + $14,704.03 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-10 12:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
