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
| Interactive sessions | 5 | 10 | 61 | 370 |
| Worker sessions | 340 | 1,183 | 4,675 | 8,397 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 61 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 91,220 | 97K | 32.8M | 6,243.7M | $3,048.14 | $16,858.06 | $9,466.72 |
| claude-opus-4-6 | 7,804 | 8K | 2.6M | 651.1M | $1,634.99 | $8,790.45 | $0.00 |
| deepseek-v4-flash-free | 16,249 | 38.5M | 3.4M | 1,352.2M | $616.39 | $3,651.18 | $2,292.10 |
| gpt-5.6-sol | 8,335 | 40.4M | 1.7M | 623.0M | $612.58 | $1,682.21 | $1,339.32 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,505 | 43K | 1.3M | 235.7M | $188.76 | $636.63 | $363.55 |
| gpt-5.5 | 6,347 | 18.5M | 1.0M | 256.2M | $131.08 | $692.00 | $591.33 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-haiku-4-5 | 2,115 | 4K | 429K | 116.7M | $13.64 | $84.08 | $196.41 |
| gpt-5.6-terra | 666 | 2.4M | 57K | 15.9M | $11.31 | $43.05 | $51.80 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 931 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **155,754** | **119.2M** | **48.3M** | **10,353.3M** | **$6,702.31** | **$34,519.05** | **$15,768.09** |

_10,780.4M total tokens processed. 96% cache hit rate._

_$50,287.15 total saved ($34,519.05 caching + $15,768.09 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 129,418 | 137K | 48.4M | 8,299.3M | $4,119.05 | $22,408.19 | $12,866.26 |
| claude-opus-4-6 | 8,013 | 8K | 2.7M | 669.1M | $1,681.77 | $9,033.42 | $0.00 |
| deepseek-v4-flash-free | 23,432 | 55.0M | 5.2M | 1,928.3M | $886.33 | $5,206.64 | $3,286.77 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 8,335 | 40.4M | 1.7M | 623.0M | $612.58 | $1,682.21 | $1,339.32 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,389 | 40K | 5.3M | 1,271.4M | $155.13 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 666 | 2.4M | 57K | 15.9M | $11.31 | $43.05 | $51.80 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **252,551** | **168.9M** | **78.6M** | **15,967.1M** | **$9,878.35** | **$50,221.38** | **$24,809.53** |

_16,652.6M total tokens processed. 95.9% cache hit rate._

_$75,030.92 total saved ($50,221.38 caching + $24,809.53 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-28 15:45 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
