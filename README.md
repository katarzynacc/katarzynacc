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
| Screen time (Linux) | 22.6h | 60.1h | 508.9h | ~7002h* |
| Interactive human attention | 2.0h | 27.2h | 101.9h | 153.5h |
| Interactive AI generation | 4.1h | 20.3h | 81.2h | 119.6h |
| Worker-classified human attention | 2.4h | 6.9h | 33.6h | 34.8h |
| Worker/headless AI generation | 97.8h | 281.4h | 605.1h | 712.1h |
| Additive observed work | 106.1h | 334.4h | 813.0h | 1,011.1h |
| Interactive sessions | 20 | 79 | 306 | 452 |
| Worker sessions | 404 | 1,655 | 4,290 | 6,175 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 66,870 | 70K | 24.7M | 3,552.0M | $1,826.45 | $9,590.61 | $5,746.28 |
| deepseek-v4-flash-free | 15,851 | 40.2M | 3.6M | 1,272.9M | $600.86 | $3,436.88 | $2,227.41 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,833 | 66K | 2.4M | 400.6M | $300.61 | $1,081.69 | $631.42 |
| gpt-5.5 | 10,502 | 30.0M | 1.7M | 448.2M | $222.74 | $1,210.31 | $1,005.08 |
| gpt-5.4 | 6,723 | 24.7M | 1.5M | 344.2M | $182.53 | $645.53 | $708.98 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| gpt-5.6-sol | 1,468 | 5.4M | 246K | 67.1M | $70.50 | $181.37 | $161.14 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-sonnet-4-0 | 350 | 3K | 80K | 22.4M | $14.18 | $60.64 | $31.79 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **150,214** | **109.6M** | **44.5M** | **8,187.7M** | **$4,155.64** | **$21,093.92** | **$13,783.59** |

_8,548.1M total tokens processed. 95.8% cache hit rate._

_$34,877.51 total saved ($21,093.92 caching + $13,783.59 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 84,528 | 89K | 32.2M | 4,422.6M | $2,307.34 | $11,941.07 | $7,242.88 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 18,056 | 45.7M | 4.1M | 1,452.1M | $687.00 | $3,920.76 | $2,542.92 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,954 | 67K | 2.5M | 409.8M | $307.02 | $1,106.52 | $645.49 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| gpt-5.6-sol | 1,468 | 5.4M | 246K | 67.1M | $70.50 | $181.37 | $161.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 187 | 754K | 34K | 8.9M | $4.85 | $24.24 | $21.91 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **188,140** | **122.9M** | **57.7M** | **10,469.6M** | **$6,002.88** | **$29,883.57** | **$17,128.30** |

_10,954.1M total tokens processed. 95.6% cache hit rate._

_$47,011.87 total saved ($29,883.57 caching + $17,128.30 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-12 18:36 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
