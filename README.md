# Kasia CC

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 1.6h | 61.2h | 486.5h | ~6910h* |
| Interactive human attention | 2.3h | 23.7h | 104.2h | 155.7h |
| Interactive AI generation | 2.8h | 20.5h | 84.0h | 122.4h |
| Worker-classified human attention | 3.6h | 9.6h | 37.2h | 38.4h |
| Worker/headless AI generation | 29.4h | 290.7h | 632.7h | 741.5h |
| Additive observed work | 37.5h | 343.0h | 848.7h | 1,048.6h |
| Interactive sessions | 21 | 74 | 320 | 466 |
| Worker sessions | 278 | 1,692 | 4,465 | 6,368 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 46 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 74,489 | 78K | 27.2M | 4,132.6M | $2,080.10 | $11,158.21 | $6,596.00 |
| deepseek-v4-flash-free | 16,517 | 41.3M | 3.7M | 1,322.0M | $622.41 | $3,569.49 | $2,307.56 |
| claude-opus-4-6 | 2,772 | 2K | 1.0M | 210.7M | $528.07 | $2,844.51 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 6,082 | 69K | 2.5M | 417.9M | $313.69 | $1,128.54 | $657.26 |
| gpt-5.5 | 10,430 | 29.7M | 1.7M | 444.7M | $220.93 | $1,200.90 | $996.97 |
| gpt-5.4 | 6,482 | 23.8M | 1.4M | 333.5M | $176.62 | $625.40 | $686.26 |
| gpt-5.6-sol | 2,723 | 10.4M | 487K | 178.1M | $159.85 | $481.08 | $368.25 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| claude-sonnet-4-0 | 255 | 2K | 50K | 15.2M | $8.88 | $41.26 | $21.37 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,114 | 4.2M | 142K | 47.4M | $3.13 | $88.98 | $104.38 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **159,953** | **113.1M** | **47.6M** | **8,975.9M** | **$4,636.23** | **$23,792.57** | **$14,885.45** |

_9,356.4M total tokens processed. 95.9% cache hit rate._

_$38,678.03 total saved ($23,792.57 caching + $14,885.45 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 92,989 | 98K | 35.1M | 5,044.1M | $2,583.12 | $13,619.29 | $8,160.59 |
| deepseek-v4-flash-free | 18,722 | 46.8M | 4.3M | 1,501.2M | $708.55 | $4,053.36 | $2,623.07 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-opus-4-6 | 2,772 | 2K | 1.0M | 210.7M | $528.07 | $2,844.51 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,203 | 71K | 2.6M | 427.1M | $320.10 | $1,153.37 | $671.33 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| gpt-5.6-sol | 2,723 | 10.4M | 487K | 178.1M | $159.85 | $481.08 | $368.25 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **199,268** | **129.1M** | **61.2M** | **11,320.6M** | **$6,519.05** | **$32,742.47** | **$18,359.11** |

_11,830.2M total tokens processed. 95.7% cache hit rate._

_$51,101.58 total saved ($32,742.47 caching + $18,359.11 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-13 19:32 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
