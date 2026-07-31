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
| Screen time (Linux) | 23.9h | 167.8h | 493.2h | ~7286h* |
| Interactive human attention | 7.1h | 18.3h | 20.3h | 134.5h |
| Interactive AI generation | 9.4h | 31.9h | 32.6h | 114.5h |
| Worker-classified human attention | 0.0h | 0.2h | 0.6h | 25.0h |
| Worker/headless AI generation | 11.7h | 47.4h | 688.3h | 1058.9h |
| Additive observed work | 28.2h | 97.8h | 741.7h | 1,327.0h |
| Interactive sessions | 18 | 31 | 38 | 391 |
| Worker sessions | 316 | 1,387 | 4,791 | 8,945 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 64 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 96,562 | 103K | 34.8M | 6,754.5M | $3,287.81 | $18,237.39 | $10,196.04 |
| claude-opus-4-6 | 8,201 | 8K | 2.7M | 674.9M | $1,691.37 | $9,111.32 | $0.00 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| deepseek-v4-flash-free | 14,535 | 34.0M | 3.0M | 1,231.7M | $555.96 | $3,325.63 | $2,068.33 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,523 | 12.9M | 721K | 187.8M | $94.00 | $507.25 | $424.48 |
| gpt-5.6-terra | 1,022 | 3.6M | 81K | 23.7M | $16.79 | $64.25 | $76.96 |
| claude-haiku-4-5 | 2,456 | 6K | 487K | 131.8M | $15.62 | $94.94 | $221.94 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 698 | 1.7M | 102K | 35.4M | $1.94 | $66.48 | $59.29 |
| **Total** | **152,490** | **115.2M** | **48.0M** | **10,521.8M** | **$6,823.38** | **$35,210.15** | **$15,876.74** |

_10,943.6M total tokens processed. 96.1% cache hit rate._

_$51,086.89 total saved ($35,210.15 caching + $15,876.74 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 134,761 | 143K | 50.3M | 8,810.2M | $4,358.75 | $23,787.70 | $13,595.68 |
| claude-opus-4-6 | 8,462 | 9K | 2.8M | 698.2M | $1,751.90 | $9,426.83 | $0.00 |
| deepseek-v4-flash-free | 23,861 | 55.5M | 5.2M | 1,966.0M | $901.58 | $5,308.40 | $3,344.25 |
| gpt-5.6-sol | 9,699 | 45.9M | 2.0M | 742.8M | $715.91 | $2,005.61 | $1,567.55 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,809 | 42K | 5.4M | 1,289.1M | $157.55 | $928.21 | $2,214.89 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,022 | 3.6M | 81K | 23.7M | $16.79 | $64.25 | $76.96 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **260,912** | **176.3M** | **81.2M** | **16,690.2M** | **$10,314.66** | **$52,453.42** | **$25,880.58** |

_17,402.4M total tokens processed. 95.9% cache hit rate._

_$78,333.99 total saved ($52,453.42 caching + $25,880.58 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-31 05:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
