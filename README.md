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
| User AI session hours | 4.7h | 31.5h | 103.9h | 154.6h |
| AI worker hours | 45.4h | 189.1h | 524.1h | 625.0h |
| AI concurrency hours | 52.6h | 249.7h | 703.7h | 893.6h |
| Interactive sessions | 3 | 57 | 241 | 346 |
| Worker sessions | 44 | 189 | 535 | 874 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,447 | 53K | 18.7M | 2,605.8M | $1,353.51 | $7,035.82 | $4,255.60 |
| deepseek-v4-flash-free | 13,817 | 35.2M | 3.1M | 1,107.4M | $524.81 | $2,990.10 | $1,943.54 |
| claude-opus-4-6 | 2,252 | 2K | 907K | 158.3M | $407.90 | $2,137.06 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-haiku-4-5 | 23,943 | 37K | 5.2M | 1,247.2M | $152.19 | $898.03 | $2,143.32 |
| gpt-5.4 | 5,650 | 20.2M | 1.2M | 260.6M | $143.54 | $488.67 | $559.11 |
| claude-sonnet-4-0 | 1,549 | 15K | 421K | 97.7M | $61.84 | $263.88 | $142.76 |
| claude-opus-4-0 | 119 | 1K | 41K | 8.2M | $27.31 | $111.72 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,131 | 5.4M | 131K | 43.0M | $3.24 | $80.68 | $114.56 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **129,871** | **93.0M** | **37.8M** | **6,969.9M** | **$3,550.80** | **$17,991.56** | **$11,731.89** |

_7,284.8M total tokens processed. 95.7% cache hit rate._

_$29,723.44 total saved ($17,991.56 caching + $11,731.89 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 66,715 | 70K | 25.8M | 3,408.7M | $1,797.96 | $9,203.71 | $5,639.81 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 15,916 | 40.4M | 3.7M | 1,278.4M | $606.85 | $3,451.75 | $2,244.01 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,252 | 2K | 907K | 158.3M | $407.90 | $2,137.06 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,979 | 38K | 5.2M | 1,248.3M | $152.40 | $898.78 | $2,145.24 |
| gpt-5.4 | 5,847 | 20.7M | 1.2M | 271.6M | $148.58 | $509.42 | $578.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,131 | 5.4M | 131K | 43.0M | $3.24 | $80.68 | $114.56 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **164,835** | **105.7M** | **50.1M** | **9,087.4M** | **$5,278.75** | **$26,247.97** | **$14,824.97** |

_9,516.4M total tokens processed. 95.5% cache hit rate._

_$41,072.94 total saved ($26,247.97 caching + $14,824.97 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-10 15:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
