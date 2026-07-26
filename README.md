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
| Screen time (Linux) | 24h | 167.8h | 488.4h | ~7197h* |
| Interactive human attention | 0.7h | 22.4h | 116.1h | 208.7h |
| Interactive AI generation | 1.8h | 18.5h | 104.6h | 173.5h |
| Worker-classified human attention | 0.0h | 5.7h | 39.6h | 59.4h |
| Worker/headless AI generation | 3.0h | 51.6h | 665.2h | 960.2h |
| Additive observed work | 5.4h | 97.4h | 914.2h | 1,387.3h |
| Interactive sessions | 4 | 14 | 258 | 535 |
| Worker sessions | 230 | 1,455 | 5,002 | 8,536 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 60 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 89,977 | 95K | 32.4M | 5,956.8M | $2,932.50 | $16,083.47 | $9,098.16 |
| claude-opus-4-6 | 7,804 | 8K | 2.6M | 651.1M | $1,634.99 | $8,790.45 | $0.00 |
| deepseek-v4-flash-free | 18,184 | 43.5M | 3.8M | 1,507.2M | $690.01 | $4,069.48 | $2,563.52 |
| gpt-5.6-sol | 7,700 | 37.3M | 1.6M | 575.4M | $566.15 | $1,553.70 | $1,237.09 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,505 | 43K | 1.3M | 235.7M | $188.76 | $636.63 | $363.55 |
| gpt-5.5 | 7,370 | 21.5M | 1.2M | 315.7M | $157.19 | $852.54 | $710.00 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-haiku-4-5 | 11,522 | 22K | 2.4M | 559.4M | $70.98 | $402.78 | $971.00 |
| gpt-5.6-terra | 455 | 1.6M | 51K | 13.6M | $8.52 | $36.74 | $38.72 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **166,045** | **123.7M** | **50.4M** | **10,673.6M** | **$6,695.76** | **$34,507.19** | **$16,453.71** |

_11,114.6M total tokens processed. 96% cache hit rate._

_$50,960.90 total saved ($34,507.19 caching + $16,453.71 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 128,175 | 136K | 48.0M | 8,012.4M | $4,003.41 | $21,633.60 | $12,497.71 |
| claude-opus-4-6 | 8,013 | 8K | 2.7M | 669.1M | $1,681.77 | $9,033.42 | $0.00 |
| deepseek-v4-flash-free | 23,432 | 55.0M | 5.2M | 1,928.3M | $886.33 | $5,206.64 | $3,286.77 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 7,700 | 37.3M | 1.6M | 575.4M | $566.15 | $1,553.70 | $1,237.09 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,387 | 40K | 5.3M | 1,271.4M | $155.10 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 455 | 1.6M | 51K | 13.6M | $8.52 | $36.74 | $38.72 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **250,460** | **165.0M** | **78.0M** | **15,630.3M** | **$9,713.46** | **$49,311.98** | **$24,325.66** |

_16,305.0M total tokens processed. 95.9% cache hit rate._

_$73,637.64 total saved ($49,311.98 caching + $24,325.66 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-26 22:45 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
