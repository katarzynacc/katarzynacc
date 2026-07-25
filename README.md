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
| Screen time (Linux) | 23.8h | 167.8h | 488.3h | ~7179h* |
| Interactive human attention | 3.5h | 26.4h | 119.0h | 208.0h |
| Interactive AI generation | 5.4h | 21.7h | 105.9h | 171.7h |
| Worker-classified human attention | 0.0h | 12.0h | 45.8h | 59.4h |
| Worker/headless AI generation | 2.1h | 61.4h | 674.8h | 957.2h |
| Additive observed work | 11.1h | 118.0h | 932.7h | 1,381.9h |
| Interactive sessions | 4 | 24 | 270 | 532 |
| Worker sessions | 176 | 1,319 | 4,877 | 8,307 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 59 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 89,845 | 95K | 32.4M | 5,930.3M | $2,922.90 | $16,012.03 | $9,063.54 |
| claude-opus-4-6 | 7,804 | 8K | 2.6M | 651.1M | $1,634.99 | $8,790.45 | $0.00 |
| deepseek-v4-flash-free | 18,346 | 43.9M | 3.9M | 1,508.5M | $692.66 | $4,073.09 | $2,571.94 |
| gpt-5.6-sol | 7,202 | 33.3M | 1.5M | 532.5M | $517.49 | $1,437.84 | $1,131.49 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 3,505 | 43K | 1.3M | 235.7M | $188.76 | $636.63 | $363.55 |
| gpt-5.5 | 7,806 | 22.7M | 1.2M | 332.2M | $165.64 | $897.15 | $747.72 |
| claude-haiku-4-5 | 20,711 | 35K | 4.5M | 1,078.3M | $132.26 | $776.40 | $1,856.40 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 287 | 1.0M | 42K | 11.3M | $6.24 | $30.52 | $28.19 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **175,034** | **120.7M** | **52.5M** | **11,138.7M** | **$6,707.60** | **$34,735.50** | **$17,234.50** |

_11,589.9M total tokens processed. 96.1% cache hit rate._

_$51,970.00 total saved ($34,735.50 caching + $17,234.50 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 128,043 | 135K | 47.9M | 7,985.9M | $3,993.81 | $21,562.16 | $12,463.08 |
| claude-opus-4-6 | 8,013 | 8K | 2.7M | 669.1M | $1,681.77 | $9,033.42 | $0.00 |
| deepseek-v4-flash-free | 22,933 | 53.8M | 5.1M | 1,883.3M | $866.95 | $5,085.02 | $3,213.71 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 7,202 | 33.3M | 1.5M | 532.5M | $517.49 | $1,437.84 | $1,131.49 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,387 | 40K | 5.3M | 1,271.4M | $155.10 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 287 | 1.0M | 42K | 11.3M | $6.24 | $30.52 | $28.19 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **249,163** | **159.4M** | **77.8M** | **15,513.6M** | **$9,633.54** | **$48,996.84** | **$24,101.85** |

_16,182.1M total tokens processed. 95.9% cache hit rate._

_$73,098.69 total saved ($48,996.84 caching + $24,101.85 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-25 22:41 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
