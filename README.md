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
| Screen time (Linux) | 23.9h | 145.4h | 488.2h | ~7055h* |
| Interactive human attention | 6.2h | 28.2h | 104.2h | 181.6h |
| Interactive AI generation | 5.0h | 30.4h | 91.2h | 150.0h |
| Worker-classified human attention | 1.5h | 12.6h | 46.1h | 47.4h |
| Worker/headless AI generation | 10.3h | 183.6h | 744.1h | 895.8h |
| Additive observed work | 22.0h | 252.6h | 974.6h | 1,263.8h |
| Interactive sessions | 15 | 66 | 300 | 511 |
| Worker sessions | 100 | 909 | 4,408 | 6,993 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 52 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 91,541 | 96K | 33.4M | 5,546.3M | $2,725.77 | $14,975.10 | $8,662.48 |
| claude-opus-4-6 | 6,955 | 7K | 2.4M | 567.0M | $1,287.92 | $7,655.67 | $0.00 |
| deepseek-v4-flash-free | 18,304 | 43.7M | 3.8M | 1,500.2M | $688.75 | $4,050.54 | $2,558.75 |
| gpt-5.6-sol | 5,911 | 24.3M | 1.1M | 405.7M | $382.94 | $1,095.62 | $849.96 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,332 | 64K | 2.1M | 356.6M | $279.35 | $962.83 | $559.32 |
| gpt-5.5 | 7,806 | 22.7M | 1.2M | 332.2M | $165.64 | $897.15 | $747.72 |
| claude-haiku-4-5 | 24,326 | 40K | 5.3M | 1,269.7M | $154.77 | $914.23 | $2,180.96 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| gpt-5.6-terra | 222 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 932 | 2.3M | 133K | 46.9M | $2.58 | $87.95 | $79.32 |
| **Total** | **180,062** | **111.4M** | **54.5M** | **10,853.7M** | **$6,159.54** | **$32,747.66** | **$17,057.07** |

_11,276.7M total tokens processed. 96.2% cache hit rate._

_$49,804.73 total saved ($32,747.66 caching + $17,057.07 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 112,563 | 119K | 42.2M | 6,591.1M | $3,298.95 | $17,795.98 | $10,444.56 |
| claude-opus-4-6 | 7,164 | 7K | 2.5M | 585.0M | $1,334.70 | $7,898.64 | $0.00 |
| deepseek-v4-flash-free | 22,506 | 52.8M | 4.9M | 1,850.6M | $850.55 | $4,996.69 | $3,153.92 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| gpt-5.6-sol | 5,911 | 24.3M | 1.1M | 405.7M | $382.94 | $1,095.62 | $849.96 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,363 | 40K | 5.3M | 1,270.8M | $154.99 | $914.98 | $2,182.88 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 222 | 879K | 41K | 10.9M | $5.81 | $29.58 | $26.20 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **231,027** | **149.1M** | **71.3M** | **13,874.2M** | **$8,440.12** | **$43,663.89** | **$21,738.78** |

_14,464.3M total tokens processed. 95.9% cache hit rate._

_$65,402.67 total saved ($43,663.89 caching + $21,738.78 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-19 09:22 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
