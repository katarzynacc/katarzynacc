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
| Screen time (Linux) | 24h | 167.8h | 488.4h | ~7159h* |
| Interactive human attention | 3.3h | 31.4h | 118.9h | 201.2h |
| Interactive AI generation | 1.3h | 23.9h | 100.0h | 161.7h |
| Worker-classified human attention | 1.3h | 14.4h | 55.9h | 59.4h |
| Worker/headless AI generation | 7.9h | 79.8h | 718.4h | 947.1h |
| Additive observed work | 13.7h | 144.9h | 978.8h | 1,354.9h |
| Interactive sessions | 3 | 42 | 290 | 529 |
| Worker sessions | 247 | 1,186 | 4,846 | 7,950 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 57 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 87,647 | 93K | 31.7M | 5,664.9M | $2,782.86 | $15,295.27 | $8,702.16 |
| claude-opus-4-6 | 7,777 | 8K | 2.6M | 651.1M | $1,628.11 | $8,790.27 | $0.00 |
| deepseek-v4-flash-free | 18,539 | 44.1M | 3.9M | 1,524.1M | $699.06 | $4,115.32 | $2,595.58 |
| gpt-5.6-sol | 7,065 | 32.5M | 1.4M | 519.9M | $505.59 | $1,404.00 | $1,104.55 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,505 | 43K | 1.3M | 235.7M | $188.76 | $636.63 | $363.55 |
| gpt-5.5 | 7,806 | 22.7M | 1.2M | 332.2M | $165.64 | $897.15 | $747.72 |
| claude-haiku-4-5 | 24,350 | 40K | 5.3M | 1,270.4M | $154.87 | $914.71 | $2,182.21 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 271 | 954K | 42K | 11.1M | $6.05 | $30.01 | $27.32 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **176,488** | **120.0M** | **52.5M** | **11,068.2M** | **$6,577.60** | **$34,164.76** | **$17,194.77** |

_11,509.5M total tokens processed. 96.2% cache hit rate._

_$51,359.53 total saved ($34,164.76 caching + $17,194.77 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 125,842 | 133K | 47.2M | 7,720.5M | $3,853.77 | $20,845.40 | $12,101.70 |
| claude-opus-4-6 | 7,986 | 8K | 2.7M | 669.1M | $1,674.88 | $9,033.24 | $0.00 |
| deepseek-v4-flash-free | 22,881 | 53.7M | 5.0M | 1,879.9M | $865.03 | $5,076.00 | $3,206.41 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 7,065 | 32.5M | 1.4M | 519.9M | $505.59 | $1,404.00 | $1,104.55 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,387 | 40K | 5.3M | 1,271.4M | $155.10 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 271 | 954K | 42K | 11.1M | $6.05 | $30.01 | $27.32 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **246,730** | **158.3M** | **77.0M** | **15,232.1M** | **$9,472.60** | **$48,236.52** | **$23,705.37** |

_15,885.1M total tokens processed. 95.9% cache hit rate._

_$71,941.89 total saved ($48,236.52 caching + $23,705.37 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-24 01:25 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
