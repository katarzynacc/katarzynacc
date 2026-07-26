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
| Screen time (Linux) | 23.8h | 167.8h | 488.3h | ~7197h* |
| Interactive human attention | 3.5h | 26.4h | 119.0h | 208.0h |
| Interactive AI generation | 5.4h | 21.7h | 105.9h | 171.7h |
| Worker-classified human attention | 0.0h | 12.0h | 45.8h | 59.4h |
| Worker/headless AI generation | 2.1h | 61.4h | 674.8h | 957.2h |
| Additive observed work | 11.1h | 118.0h | 932.7h | 1,381.9h |
| Interactive sessions | 6 | 26 | 272 | 534 |
| Worker sessions | 362 | 1,505 | 5,063 | 8,493 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 59 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 89,846 | 95K | 32.4M | 5,930.3M | $2,922.90 | $16,012.03 | $9,063.54 |
| claude-opus-4-6 | 7,804 | 8K | 2.6M | 651.1M | $1,634.99 | $8,790.45 | $0.00 |
| deepseek-v4-flash-free | 18,194 | 43.2M | 3.8M | 1,499.8M | $686.52 | $4,049.55 | $2,550.12 |
| gpt-5.6-sol | 7,332 | 34.3M | 1.5M | 538.5M | $525.68 | $1,454.16 | $1,150.48 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,505 | 43K | 1.3M | 235.7M | $188.76 | $636.63 | $363.55 |
| gpt-5.5 | 7,806 | 22.7M | 1.2M | 332.2M | $165.64 | $897.15 | $747.72 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-haiku-4-5 | 11,848 | 23K | 2.5M | 581.1M | $73.41 | $418.42 | $1,006.43 |
| gpt-5.6-terra | 422 | 1.5M | 46K | 12.8M | $8.00 | $34.58 | $36.39 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **166,285** | **121.4M** | **50.4M** | **10,640.3M** | **$6,652.56** | **$34,374.36** | **$16,389.91** |

_11,079.2M total tokens processed. 96% cache hit rate._

_$50,764.27 total saved ($34,374.36 caching + $16,389.91 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 128,044 | 135K | 47.9M | 7,985.9M | $3,993.81 | $21,562.16 | $12,463.08 |
| claude-opus-4-6 | 8,013 | 8K | 2.7M | 669.1M | $1,681.77 | $9,033.42 | $0.00 |
| deepseek-v4-flash-free | 23,264 | 54.3M | 5.1M | 1,910.7M | $878.19 | $5,159.05 | $3,256.01 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 7,332 | 34.3M | 1.5M | 538.5M | $525.68 | $1,454.16 | $1,150.48 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,387 | 40K | 5.3M | 1,271.4M | $155.10 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 422 | 1.5M | 46K | 12.8M | $8.00 | $34.58 | $36.39 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **249,760** | **161.3M** | **77.9M** | **15,548.6M** | **$9,654.73** | **$49,091.24** | **$24,171.35** |

_16,219.1M total tokens processed. 95.9% cache hit rate._

_$73,262.59 total saved ($49,091.24 caching + $24,171.35 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-26 20:44 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
