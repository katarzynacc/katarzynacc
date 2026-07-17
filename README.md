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
| Screen time (Linux) | 23.9h | 144.1h | 488.3h | ~7032h* |
| Interactive human attention | 5.6h | 24.0h | 103.6h | 175.4h |
| Interactive AI generation | 7.1h | 29.5h | 91.4h | 144.9h |
| Worker-classified human attention | 1.0h | 13.5h | 44.7h | 45.9h |
| Worker/headless AI generation | 18.0h | 270.7h | 739.7h | 885.0h |
| Additive observed work | 31.4h | 336.3h | 969.3h | 1,241.3h |
| Interactive sessions | 12 | 67 | 299 | 499 |
| Worker sessions | 140 | 1,142 | 4,373 | 6,905 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 51 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 88,895 | 93K | 32.4M | 5,275.9M | $2,599.08 | $14,245.10 | $8,277.79 |
| claude-opus-4-6 | 6,495 | 6K | 2.2M | 527.7M | $1,198.18 | $7,125.00 | $0.00 |
| deepseek-v4-flash-free | 17,687 | 42.4M | 3.7M | 1,442.1M | $664.27 | $3,893.83 | $2,466.46 |
| gpt-5.6-sol | 5,456 | 22.6M | 1.0M | 370.1M | $351.02 | $999.52 | $779.23 |
| claude-sonnet-4-5 | 6,558 | 75K | 2.6M | 452.5M | $337.96 | $1,221.93 | $705.94 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| gpt-5.5 | 10,238 | 29.3M | 1.7M | 436.4M | $217.07 | $1,178.34 | $979.49 |
| claude-haiku-4-5 | 24,241 | 39K | 5.3M | 1,265.3M | $154.27 | $911.06 | $2,173.69 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **179,463** | **114.9M** | **54.1M** | **10,646.4M** | **$6,006.91** | **$31,797.51** | **$16,876.41** |

_11,069.6M total tokens processed. 96.2% cache hit rate._

_$48,673.92 total saved ($31,797.51 caching + $16,876.41 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 109,917 | 116K | 41.2M | 6,320.7M | $3,172.26 | $17,065.98 | $10,059.87 |
| claude-opus-4-6 | 6,704 | 7K | 2.3M | 545.7M | $1,244.95 | $7,367.96 | $0.00 |
| deepseek-v4-flash-free | 21,887 | 51.4M | 4.8M | 1,792.2M | $825.95 | $4,839.08 | $3,061.20 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.6-sol | 5,456 | 22.6M | 1.0M | 370.1M | $351.02 | $999.52 | $779.23 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,278 | 39K | 5.3M | 1,266.4M | $154.49 | $911.81 | $2,175.62 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **226,729** | **146.0M** | **69.9M** | **13,464.2M** | **$8,165.75** | **$42,141.04** | **$21,179.29** |

_14,040.6M total tokens processed. 95.9% cache hit rate._

_$63,320.33 total saved ($42,141.04 caching + $21,179.29 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-17 23:30 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
