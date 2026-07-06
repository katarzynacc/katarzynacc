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
| Screen time (Linux) | 8h | 4.7h | 84.2h | ~1,351h* |
| User AI session hours | 9.0h | 42.1h | 110.2h | 140.4h |
| AI worker hours | 30.7h | 168.0h | 415.0h | 494.6h |
| AI concurrency hours | 43.8h | 243.7h | 602.9h | 739.1h |
| Interactive sessions | 20 | 108 | 251 | 318 |
| Worker sessions | 48 | 179 | 486 | 766 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 33,607 | 35K | 12.4M | 1,821.1M | $920.87 | $4,917.05 | $2,935.46 |
| deepseek-v4-flash-free | 14,000 | 34.1M | 3.2M | 1,117.5M | $528.49 | $3,017.26 | $1,949.01 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-0 | 1,486 | 14K | 390K | 110.1M | $325.74 | $1,486.60 | $0.00 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 11,157 | 32.7M | 1.9M | 490.8M | $242.88 | $1,325.40 | $1,097.19 |
| claude-haiku-4-5 | 23,248 | 37K | 5.0M | 1,201.6M | $147.12 | $865.19 | $2,068.32 |
| claude-sonnet-4-0 | 3,105 | 31K | 902K | 193.8M | $125.02 | $523.40 | $287.15 |
| claude-opus-4-6 | 575 | 642 | 235K | 49.5M | $119.47 | $669.49 | $0.00 |
| gpt-5.4 | 3,726 | 13.2M | 732K | 168.0M | $92.48 | $315.07 | $360.19 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **114,455** | **88.2M** | **31.8M** | **6,283.2M** | **$3,206.74** | **$16,235.22** | **$10,529.94** |

_6,570.8M total tokens processed. 95.6% cache hit rate._

_$26,765.16 total saved ($16,235.22 caching + $10,529.94 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 46,661 | 49K | 18.2M | 2,466.0M | $1,282.68 | $6,658.36 | $4,057.43 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 14,000 | 34.1M | 3.2M | 1,117.5M | $528.49 | $3,017.26 | $1,949.01 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,233 | 59K | 2.3M | 364.0M | $274.22 | $982.88 | $576.55 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,280 | 37K | 5.0M | 1,202.6M | $147.28 | $865.93 | $2,070.21 |
| claude-opus-4-6 | 575 | 642 | 235K | 49.5M | $119.47 | $669.49 | $0.00 |
| gpt-5.4 | 3,726 | 13.2M | 732K | 168.0M | $92.48 | $315.07 | $360.19 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 991 | 5.0M | 113K | 36.6M | $2.87 | $68.78 | $102.59 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **137,767** | **91.4M** | **40.6M** | **7,689.1M** | **$4,314.05** | **$21,479.53** | **$12,598.08** |

_8,054.8M total tokens processed. 95.5% cache hit rate._

_$34,077.61 total saved ($21,479.53 caching + $12,598.08 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-06 09:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
