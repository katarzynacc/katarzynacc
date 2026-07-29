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
| Interactive sessions | 6 | 13 | 46 | 373 |
| Worker sessions | 394 | 1,239 | 4,778 | 8,630 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 62 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 92,739 | 98K | 33.3M | 6,388.6M | $3,115.83 | $17,249.33 | $9,671.20 |
| claude-opus-4-6 | 7,773 | 8K | 2.6M | 646.2M | $1,624.04 | $8,723.84 | $0.00 |
| gpt-5.6-sol | 9,003 | 43.3M | 1.9M | 693.1M | $669.15 | $1,871.54 | $1,467.41 |
| deepseek-v4-flash-free | 15,216 | 36.0M | 3.2M | 1,284.1M | $582.42 | $3,467.15 | $2,167.40 |
| claude-sonnet-4-5 | 9,654 | 25K | 2.3M | 375.8M | $206.60 | $1,014.85 | $589.44 |
| claude-sonnet-4-5 | 2,766 | 33K | 1.0M | 192.2M | $153.75 | $519.15 | $293.74 |
| gpt-5.5 | 6,208 | 18.0M | 990K | 251.3M | $128.05 | $678.69 | $577.83 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 793 | 3.0M | 61K | 17.2M | $13.24 | $46.58 | $60.76 |
| claude-haiku-4-5 | 2,036 | 4K | 408K | 114.1M | $13.20 | $82.20 | $191.19 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 776 | 1.9M | 112K | 37.8M | $2.12 | $70.91 | $64.90 |
| **Total** | **151,178** | **119.3M** | **47.1M** | **10,240.3M** | **$6,634.05** | **$34,173.23** | **$15,571.08** |

_10,657.0M total tokens processed. 96.1% cache hit rate._

_$49,744.31 total saved ($34,173.23 caching + $15,571.08 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 130,937 | 139K | 48.9M | 8,444.2M | $4,186.74 | $22,799.46 | $13,070.74 |
| claude-opus-4-6 | 8,030 | 8K | 2.7M | 669.5M | $1,683.81 | $9,038.36 | $0.00 |
| deepseek-v4-flash-free | 23,551 | 55.1M | 5.2M | 1,939.0M | $890.70 | $5,235.45 | $3,303.20 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| gpt-5.6-sol | 9,003 | 43.3M | 1.9M | 693.1M | $669.15 | $1,871.54 | $1,467.41 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,389 | 40K | 5.3M | 1,271.4M | $155.13 | $915.47 | $2,184.14 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 793 | 3.0M | 61K | 17.2M | $13.24 | $46.58 | $60.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **255,001** | **172.6M** | **79.3M** | **16,194.5M** | **$10,010.95** | **$50,839.27** | **$25,167.50** |

_16,888.8M total tokens processed. 95.9% cache hit rate._

_$76,006.77 total saved ($50,839.27 caching + $25,167.50 model routing vs all-Opus)._

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
_Stats auto-updated 2026-07-29 21:45 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
