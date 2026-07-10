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
| Screen time (Linux) | 24h | 3.7h | 63.4h | ~1,351h* |
| User AI session hours | 1.7h | 29.9h | 101.2h | 151.7h |
| AI worker hours | 38.6h | 188.9h | 517.3h | 618.2h |
| AI concurrency hours | 41.7h | 248.1h | 693.2h | 882.7h |
| Interactive sessions | 2 | 60 | 241 | 345 |
| Worker sessions | 37 | 184 | 528 | 867 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 49,645 | 52K | 18.4M | 2,557.0M | $1,329.36 | $6,904.10 | $4,178.86 |
| deepseek-v4-flash-free | 13,646 | 34.7M | 3.1M | 1,090.8M | $517.34 | $2,945.38 | $1,915.91 |
| claude-opus-4-6 | 1,903 | 2K | 771K | 137.3M | $351.10 | $1,853.57 | $0.00 |
| claude-sonnet-4-5 | 14,368 | 38K | 3.5M | 572.0M | $317.19 | $1,544.43 | $900.33 |
| claude-sonnet-4-5 | 5,573 | 63K | 2.4M | 385.1M | $288.85 | $1,039.99 | $607.05 |
| gpt-5.5 | 10,643 | 30.3M | 1.8M | 453.2M | $225.73 | $1,223.66 | $1,018.14 |
| claude-haiku-4-5 | 23,867 | 37K | 5.2M | 1,241.4M | $151.54 | $893.88 | $2,133.63 |
| gpt-5.4 | 5,543 | 19.8M | 1.1M | 250.8M | $139.56 | $470.32 | $544.07 |
| claude-sonnet-4-0 | 1,549 | 15K | 421K | 97.7M | $61.84 | $263.88 | $142.76 |
| claude-opus-4-0 | 119 | 1K | 41K | 8.2M | $27.31 | $111.72 | $0.00 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.5-fast | 183 | 1.0M | 44K | 22.3M | $9.17 | $60.30 | $42.64 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **128,257** | **91.8M** | **37.3M** | **6,862.6M** | **$3,457.44** | **$17,498.94** | **$11,592.64** |

_7,173.1M total tokens processed. 95.7% cache hit rate._

_$29,091.59 total saved ($17,498.94 caching + $11,592.64 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 65,850 | 69K | 25.4M | 3,355.9M | $1,771.81 | $9,060.94 | $5,556.76 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| deepseek-v4-flash-free | 15,677 | 39.7M | 3.6M | 1,257.1M | $596.76 | $3,394.37 | $2,206.69 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-opus-4-6 | 1,903 | 2K | 771K | 137.3M | $351.10 | $1,853.57 | $0.00 |
| claude-sonnet-4-5 | 5,694 | 64K | 2.4M | 394.3M | $295.26 | $1,064.82 | $621.12 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| claude-haiku-4-5 | 23,903 | 37K | 5.2M | 1,242.5M | $151.75 | $894.63 | $2,135.55 |
| gpt-5.4 | 5,740 | 20.4M | 1.2M | 261.9M | $144.61 | $491.08 | $563.10 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.4-mini | 1,022 | 5.1M | 117K | 37.5M | $2.93 | $70.49 | $104.42 |
| north-mini-code-free | 14 | 394K | 1K | 0 | $1.23 | $0.00 | $4.80 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **163,090** | **104.3M** | **49.5M** | **8,971.3M** | **$5,180.78** | **$25,731.64** | **$14,669.74** |

_9,395.8M total tokens processed. 95.5% cache hit rate._

_$40,401.37 total saved ($25,731.64 caching + $14,669.74 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-10 11:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
