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
| Interactive sessions | 17 | 70 | 316 | 462 |
| Worker sessions | 254 | 1,668 | 4,441 | 6,344 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 46 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 73,399 | 77K | 26.8M | 4,037.1M | $2,039.15 | $10,900.38 | $6,455.51 |
| deepseek-v4-flash-free | 16,445 | 41.3M | 3.7M | 1,316.9M | $620.38 | $3,555.67 | $2,299.83 |
| claude-opus-4-6 | 2,683 | 2K | 1.0M | 195.0M | $498.58 | $2,632.51 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,833 | 66K | 2.4M | 400.6M | $300.61 | $1,081.69 | $631.42 |
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
| gpt-5.4-mini | 1,144 | 4.6M | 144K | 47.5M | $3.22 | $89.11 | $108.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **158,483** | **113.4M** | **47.0M** | **8,842.3M** | **$4,550.77** | **$23,262.20** | **$14,715.82** |

_9,218.9M total tokens processed. 95.9% cache hit rate._

_$37,978.02 total saved ($23,262.20 caching + $14,715.82 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 91,902 | 97K | 34.6M | 4,948.9M | $2,542.32 | $13,362.04 | $8,020.63 |
| deepseek-v4-flash-free | 18,650 | 46.7M | 4.3M | 1,496.1M | $706.52 | $4,039.54 | $2,615.34 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-opus-4-6 | 2,683 | 2K | 1.0M | 195.0M | $498.58 | $2,632.51 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,954 | 67K | 2.5M | 409.8M | $307.02 | $1,106.52 | $645.49 |
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
| **Total** | **197,771** | **129.0M** | **60.7M** | **11,187.1M** | **$6,433.65** | **$32,212.56** | **$18,185.59** |

_11,692.6M total tokens processed. 95.7% cache hit rate._

_$50,398.14 total saved ($32,212.56 caching + $18,185.59 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-13 15:31 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
