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
| Screen time (Linux) | 24h | 167.8h | 488.5h | ~7234h* |
| Interactive human attention | 1.4h | 5.6h | 22.4h | 121.8h |
| Interactive AI generation | 3.5h | 10.4h | 19.4h | 92.9h |
| Worker-classified human attention | 0.0h | 0.0h | 2.6h | 24.8h |
| Worker/headless AI generation | 3.5h | 55.8h | 720.8h | 1033.0h |
| Additive observed work | 8.4h | 71.9h | 764.3h | 1,266.8h |
| Interactive sessions | 6 | 11 | 62 | 371 |
| Worker sessions | 396 | 1,239 | 4,731 | 8,453 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 61 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 91,633 | 97K | 32.9M | 6,269.2M | $3,063.37 | $16,926.86 | $9,503.35 |
| claude-opus-4-6 | 7,820 | 8K | 2.6M | 651.4M | $1,636.90 | $8,794.95 | $0.00 |
| gpt-5.6-sol | 8,889 | 42.6M | 1.9M | 680.7M | $658.25 | $1,838.06 | $1,442.74 |
| deepseek-v4-flash-free | 16,083 | 38.3M | 3.4M | 1,345.0M | $612.96 | $3,631.75 | $2,279.86 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,477 | 42K | 1.3M | 234.7M | $187.82 | $633.75 | $361.48 |
| gpt-5.5 | 6,347 | 18.5M | 1.0M | 256.2M | $131.08 | $692.00 | $591.33 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-haiku-4-5 | 2,036 | 4K | 408K | 114.1M | $13.20 | $82.20 | $191.19 |
| gpt-5.6-terra | 684 | 2.5M | 58K | 16.1M | $11.57 | $43.58 | $52.99 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 931 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **156,482** | **121.3M** | **48.5M** | **10,426.2M** | **$6,760.57** | **$34,724.54** | **$15,889.80** |

_10,856.9M total tokens processed. 96% cache hit rate._

_$50,614.34 total saved ($34,724.54 caching + $15,889.80 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 129,831 | 138K | 48.5M | 8,324.8M | $4,134.28 | $22,476.99 | $12,902.89 |
| claude-opus-4-6 | 8,029 | 8K | 2.7M | 669.4M | $1,683.68 | $9,037.92 | $0.00 |
| deepseek-v4-flash-free | 23,432 | 55.0M | 5.2M | 1,928.3M | $886.33 | $5,206.64 | $3,286.77 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 8,889 | 42.6M | 1.9M | 680.7M | $658.25 | $1,838.06 | $1,442.74 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,389 | 40K | 5.3M | 1,271.4M | $155.13 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 684 | 2.5M | 58K | 16.1M | $11.57 | $43.58 | $52.99 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **253,552** | **171.2M** | **78.8M** | **16,050.9M** | **$9,941.42** | **$50,451.06** | **$24,950.77** |

_16,740.5M total tokens processed. 95.9% cache hit rate._

_$75,401.83 total saved ($50,451.06 caching + $24,950.77 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-28 20:44 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
