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
| Screen time (Linux) | 24h | 61.2h | 488.3h | ~6910h* |
| Interactive human attention | 3.4h | 19.7h | 106.9h | 159.2h |
| Interactive AI generation | 4.8h | 19.5h | 88.3h | 127.2h |
| Worker-classified human attention | 1.0h | 10.3h | 38.3h | 39.5h |
| Worker/headless AI generation | 58.9h | 300.3h | 688.7h | 800.4h |
| Additive observed work | 68.1h | 348.4h | 912.7h | 1,116.7h |
| Interactive sessions | 15 | 57 | 322 | 469 |
| Worker sessions | 194 | 1,397 | 4,377 | 6,374 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 47 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 75,559 | 79K | 27.5M | 4,270.2M | $2,137.14 | $11,529.65 | $6,781.01 |
| deepseek-v4-flash-free | 16,517 | 41.3M | 3.7M | 1,322.0M | $622.41 | $3,569.49 | $2,307.56 |
| claude-opus-4-6 | 2,868 | 3K | 1.0M | 216.4M | $539.64 | $2,921.75 | $0.00 |
| claude-sonnet-4-5 | 6,558 | 75K | 2.7M | 456.8M | $340.19 | $1,233.56 | $712.82 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| gpt-5.5 | 10,430 | 29.7M | 1.7M | 444.7M | $220.93 | $1,200.90 | $996.97 |
| gpt-5.4 | 6,347 | 23.4M | 1.4M | 325.8M | $173.02 | $610.88 | $672.51 |
| gpt-5.6-sol | 2,723 | 10.4M | 487K | 178.1M | $159.85 | $481.08 | $368.25 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| claude-sonnet-4-0 | 246 | 1K | 48K | 15.1M | $8.73 | $40.87 | $21.12 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,108 | 4.2M | 142K | 47.4M | $3.11 | $88.96 | $103.52 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **161,445** | **112.6M** | **48.0M** | **9,150.2M** | **$4,727.57** | **$24,331.34** | **$15,111.15** |

_9,536.9M total tokens processed. 95.9% cache hit rate._

_$39,442.49 total saved ($24,331.34 caching + $15,111.15 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 94,107 | 99K | 35.4M | 5,182.7M | $2,641.09 | $13,993.33 | $8,347.80 |
| deepseek-v4-flash-free | 18,722 | 46.8M | 4.3M | 1,501.2M | $708.55 | $4,053.36 | $2,623.07 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-opus-4-6 | 2,868 | 3K | 1.0M | 216.4M | $539.64 | $2,921.75 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,679 | 77K | 2.7M | 466.0M | $346.60 | $1,258.39 | $726.89 |
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
| **Total** | **200,958** | **129.1M** | **61.7M** | **11,503.7M** | **$6,615.09** | **$33,298.78** | **$18,601.88** |

_12,020.3M total tokens processed. 95.7% cache hit rate._

_$51,900.65 total saved ($33,298.78 caching + $18,601.88 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-13 23:31 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
