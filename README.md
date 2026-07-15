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
| Screen time (Linux) | 24h | 72.2h | 488.3h | ~6961h* |
| Interactive human attention | 1.5h | 17.9h | 102.1h | 160.7h |
| Interactive AI generation | 2.7h | 19.2h | 87.1h | 129.9h |
| Worker-classified human attention | 5.5h | 14.1h | 43.7h | 45.0h |
| Worker/headless AI generation | 37.3h | 299.0h | 717.5h | 837.6h |
| Additive observed work | 46.7h | 348.7h | 940.6h | 1,163.4h |
| Interactive sessions | 13 | 58 | 301 | 481 |
| Worker sessions | 299 | 1,451 | 4,401 | 6,668 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 48 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 82,495 | 86K | 29.9M | 4,729.8M | $2,348.07 | $12,770.59 | $7,476.54 |
| claude-opus-4-6 | 5,804 | 6K | 1.9M | 479.3M | $1,082.86 | $6,471.38 | $0.00 |
| deepseek-v4-flash-free | 18,014 | 43.3M | 3.9M | 1,454.4M | $675.17 | $3,927.10 | $2,505.50 |
| claude-sonnet-4-5 | 6,671 | 77K | 2.7M | 462.9M | $345.20 | $1,249.87 | $721.83 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| gpt-5.6-sol | 4,203 | 15.9M | 796K | 274.9M | $249.37 | $742.40 | $569.06 |
| gpt-5.5 | 10,429 | 29.7M | 1.7M | 444.7M | $220.89 | $1,200.90 | $996.74 |
| gpt-5.4 | 6,031 | 22.3M | 1.4M | 315.2M | $166.22 | $591.10 | $645.98 |
| claude-haiku-4-5 | 24,129 | 38K | 5.2M | 1,261.3M | $153.73 | $908.16 | $2,166.69 |
| claude-opus-4-7 | 137 | 167 | 59K | 6.3M | $21.93 | $85.56 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,067 | 3.7M | 140K | 47.3M | $2.98 | $88.72 | $97.87 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **173,805** | **118.6M** | **51.8M** | **10,082.2M** | **$5,613.36** | **$29,696.31** | **$16,161.14** |

_10,492.8M total tokens processed. 96.1% cache hit rate._

_$45,857.45 total saved ($29,696.31 caching + $16,161.14 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 101,299 | 106K | 37.9M | 5,652.4M | $2,858.39 | $15,261.56 | $9,061.90 |
| claude-opus-4-6 | 5,804 | 6K | 1.9M | 479.3M | $1,082.86 | $6,471.38 | $0.00 |
| deepseek-v4-flash-free | 20,219 | 48.8M | 4.5M | 1,633.6M | $761.31 | $4,410.98 | $2,821.01 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.6-sol | 4,203 | 15.9M | 796K | 274.9M | $249.37 | $742.40 | $569.06 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 24,166 | 39K | 5.2M | 1,262.3M | $153.95 | $908.91 | $2,168.62 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-terra | 189 | 770K | 34K | 8.9M | $4.90 | $24.28 | $22.13 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **214,178** | **136.6M** | **65.7M** | **12,471.6M** | **$7,522.96** | **$38,751.92** | **$19,723.96** |

_13,015.2M total tokens processed. 95.8% cache hit rate._

_$58,475.88 total saved ($38,751.92 caching + $19,723.96 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-15 20:34 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
