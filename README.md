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
| Worker/headless AI generation | 18.2h | 271.1h | 740.2h | 885.5h |
| Additive observed work | 31.7h | 336.7h | 969.8h | 1,241.7h |
| Interactive sessions | 19 | 74 | 306 | 506 |
| Worker sessions | 176 | 1,178 | 4,409 | 6,941 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 51 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 89,855 | 94K | 32.8M | 5,372.4M | $2,645.87 | $14,505.74 | $8,418.20 |
| claude-opus-4-6 | 6,558 | 6K | 2.2M | 531.8M | $1,206.70 | $7,180.43 | $0.00 |
| deepseek-v4-flash-free | 17,973 | 43.0M | 3.8M | 1,468.9M | $675.62 | $3,966.11 | $2,508.73 |
| gpt-5.6-sol | 5,803 | 23.9M | 1.1M | 396.2M | $374.49 | $1,069.90 | $831.23 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,643 | 68K | 2.2M | 378.5M | $294.29 | $1,021.99 | $592.93 |
| gpt-5.5 | 9,110 | 26.6M | 1.5M | 382.6M | $192.70 | $1,033.24 | $869.41 |
| claude-haiku-4-5 | 24,241 | 39K | 5.3M | 1,265.3M | $154.27 | $911.06 | $2,173.69 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| gpt-5.6-terra | 222 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **179,070** | **114.2M** | **54.0M** | **10,671.8M** | **$6,018.34** | **$31,884.99** | **$16,892.08** |

_11,092.9M total tokens processed. 96.2% cache hit rate._

_$48,777.08 total saved ($31,884.99 caching + $16,892.08 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 110,877 | 117K | 41.6M | 6,417.2M | $3,219.05 | $17,326.62 | $10,200.28 |
| claude-opus-4-6 | 6,767 | 7K | 2.3M | 549.8M | $1,253.48 | $7,423.40 | $0.00 |
| deepseek-v4-flash-free | 22,173 | 52.0M | 4.9M | 1,819.0M | $837.30 | $4,911.36 | $3,103.47 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| gpt-5.6-sol | 5,804 | 23.9M | 1.1M | 396.2M | $374.58 | $1,069.90 | $831.45 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,278 | 39K | 5.3M | 1,266.4M | $154.49 | $911.81 | $2,175.62 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 222 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **228,419** | **148.0M** | **70.4M** | **13,619.6M** | **$8,256.89** | **$42,605.08** | **$21,418.28** |

_14,201.8M total tokens processed. 95.9% cache hit rate._

_$64,023.36 total saved ($42,605.08 caching + $21,418.28 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-18 14:10 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
