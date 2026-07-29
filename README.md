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
| Screen time (Linux) | 24h | 167.8h | 488.5h | ~7252h* |
| Interactive human attention | 5.2h | 10.8h | 23.1h | 127.0h |
| Interactive AI generation | 3.3h | 13.6h | 20.1h | 96.2h |
| Worker-classified human attention | 0.2h | 0.2h | 2.8h | 25.0h |
| Worker/headless AI generation | 10.9h | 54.9h | 715.6h | 1043.9h |
| Additive observed work | 19.4h | 79.5h | 760.5h | 1,286.2h |
| Interactive sessions | 4 | 11 | 44 | 371 |
| Worker sessions | 357 | 1,202 | 4,741 | 8,593 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 62 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 92,631 | 98K | 33.3M | 6,365.8M | $3,106.65 | $17,187.73 | $9,641.54 |
| claude-opus-4-6 | 7,773 | 8K | 2.6M | 646.2M | $1,624.04 | $8,723.84 | $0.00 |
| gpt-5.6-sol | 8,954 | 43.0M | 1.9M | 687.0M | $664.26 | $1,855.14 | $1,456.20 |
| deepseek-v4-flash-free | 15,695 | 37.6M | 3.3M | 1,313.3M | $598.76 | $3,545.99 | $2,227.71 |
| claude-sonnet-4-5 | 11,610 | 30K | 2.7M | 453.8M | $249.02 | $1,225.34 | $710.49 |
| claude-sonnet-4-5 | 2,783 | 34K | 1.0M | 193.4M | $154.84 | $522.37 | $295.52 |
| gpt-5.5 | 6,347 | 18.5M | 1.0M | 256.2M | $131.08 | $692.00 | $591.33 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-haiku-4-5 | 2,036 | 4K | 408K | 114.1M | $13.20 | $82.20 | $191.19 |
| gpt-5.6-terra | 761 | 2.8M | 60K | 16.9M | $12.76 | $45.68 | $58.54 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 850 | 2.1M | 122K | 41.6M | $2.34 | $78.10 | $71.77 |
| **Total** | **153,654** | **121.2M** | **47.7M** | **10,328.2M** | **$6,682.60** | **$34,407.38** | **$15,731.49** |

_10,750.3M total tokens processed. 96.1% cache hit rate._

_$50,138.87 total saved ($34,407.38 caching + $15,731.49 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 130,829 | 139K | 48.8M | 8,421.4M | $4,177.56 | $22,737.86 | $13,041.08 |
| claude-opus-4-6 | 8,030 | 8K | 2.7M | 669.5M | $1,683.81 | $9,038.36 | $0.00 |
| deepseek-v4-flash-free | 23,432 | 55.0M | 5.2M | 1,928.3M | $886.33 | $5,206.64 | $3,286.77 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 8,954 | 43.0M | 1.9M | 687.0M | $664.26 | $1,855.14 | $1,456.20 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,389 | 40K | 5.3M | 1,271.4M | $155.13 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 761 | 2.8M | 60K | 16.9M | $12.76 | $45.68 | $58.54 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **254,693** | **172.0M** | **79.2M** | **16,154.6M** | **$9,992.03** | **$50,731.56** | **$25,107.97** |

_16,847.7M total tokens processed. 95.9% cache hit rate._

_$75,839.53 total saved ($50,731.56 caching + $25,107.97 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-29 14:44 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
