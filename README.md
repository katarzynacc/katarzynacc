# Kasia CC

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 23.9h | 63.2h | 508.8h | ~7002h* |
| Interactive human attention | 2.3h | 27.4h | 102.3h | 153.8h |
| Interactive AI generation | 4.9h | 21.0h | 82.0h | 120.4h |
| Worker-classified human attention | 2.4h | 6.9h | 33.6h | 34.8h |
| Worker/headless AI generation | 93.1h | 277.7h | 604.6h | 713.3h |
| Additive observed work | 102.6h | 331.5h | 813.8h | 1,013.5h |
| Interactive sessions | 15 | 73 | 302 | 448 |
| Worker sessions | 314 | 1,573 | 4,225 | 6,125 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 45 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 63,601 | 67K | 23.5M | 3,367.9M | $1,732.17 | $9,093.46 | $5,452.73 |
| deepseek-v4-flash-free | 15,274 | 39.2M | 3.4M | 1,223.6M | $580.34 | $3,303.82 | $2,149.58 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,763 | 65K | 2.4M | 398.6M | $299.17 | $1,076.42 | $628.28 |
| gpt-5.5 | 10,624 | 30.3M | 1.8M | 453.1M | $225.73 | $1,223.63 | $1,018.13 |
| gpt-5.4 | 6,724 | 24.7M | 1.5M | 344.2M | $182.56 | $645.53 | $709.14 |
| claude-haiku-4-5 | 24,047 | 38K | 5.2M | 1,253.8M | $152.88 | $902.80 | $2,154.42 |
| gpt-5.6-sol | 1,221 | 4.5M | 207K | 52.9M | $57.29 | $143.09 | $130.64 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-sonnet-4-0 | 575 | 5K | 143K | 32.6M | $21.65 | $88.18 | $47.87 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **146,130** | **107.3M** | **43.2M** | **7,936.8M** | **$4,030.98** | **$20,431.42** | **$13,373.66** |

_8,288.7M total tokens processed. 95.8% cache hit rate._

_$33,805.08 total saved ($20,431.42 caching + $13,373.66 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 81,097 | 85K | 30.9M | 4,233.0M | $2,209.05 | $11,429.17 | $6,939.33 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 17,479 | 44.7M | 4.0M | 1,402.8M | $666.48 | $3,787.69 | $2,465.09 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-opus-4-6 | 2,275 | 2K | 915K | 158.7M | $411.66 | $2,142.98 | $0.00 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 5,884 | 67K | 2.5M | 407.8M | $305.58 | $1,101.25 | $642.35 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,084 | 38K | 5.2M | 1,254.9M | $153.11 | $903.56 | $2,156.34 |
| gpt-5.6-sol | 1,221 | 4.5M | 207K | 52.9M | $57.29 | $143.09 | $130.64 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **183,546** | **120.3M** | **56.2M** | **10,198.1M** | **$5,863.73** | **$29,165.45** | **$16,679.10** |

_10,672.2M total tokens processed. 95.6% cache hit rate._

_$45,844.55 total saved ($29,165.45 caching + $16,679.10 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-12 01:11 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
