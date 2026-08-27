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
| Screen time (Linux) | 0h | 108.6h | 431.5h | ~7230h* |
| Interactive human attention | 2.7h | 15.6h | 64.6h | 82.9h |
| Interactive AI generation | 4.0h | 27.6h | 183.2h | 215.1h |
| Worker-classified human attention | 1.9h | 10.7h | 19.2h | 19.5h |
| Worker/headless AI generation | 16.9h | 101.6h | 314.0h | 1048.3h |
| Additive observed work | 25.1h | 154.8h | 578.8h | 1,363.4h |
| Interactive sessions | 2 | 15 | 71 | 101 |
| Worker sessions | 309 | 1,492 | 5,374 | 10,395 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 57 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 57,819 | 63K | 21.9M | 6,953.1M | $3,327.46 | $18,773.47 | $9,659.32 |
| claude-opus-4-6 | 4,046 | 4K | 1.3M | 414.5M | $940.65 | $5,595.77 | $0.00 |
| gpt-5.6-sol | 4,296 | 20.9M | 942K | 387.7M | $354.92 | $1,046.92 | $773.56 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 3,842 | 20.4M | 955K | 211.0M | $103.45 | $569.90 | $555.65 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| claude-haiku-4-5 | 2,856 | 16K | 551K | 160.9M | $21.46 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,165 | 29.9M | 219K | 44.1M | $7.83 | $119.15 | $425.08 |
| gpt-5.6-sol-fast | 53 | 142K | 14K | 3.5M | $3.33 | $9.55 | $6.82 |
| **Total** | **79,218** | **86.8M** | **27.0M** | **8,566.5M** | **$5,152.64** | **$28,041.81** | **$12,296.93** |

_8,947.1M total tokens processed. 95.7% cache hit rate._

_$40,338.74 total saved ($28,041.81 caching + $12,296.93 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,102 | 161K | 55.1M | 13,281.3M | $6,416.58 | $35,859.56 | $19,248.68 |
| claude-opus-4-6 | 11,815 | 12K | 4.0M | 1,060.6M | $2,563.92 | $14,318.63 | $0.00 |
| gpt-5.6-sol | 13,185 | 63.5M | 2.8M | 1,068.5M | $1,013.17 | $2,884.97 | $2,216.30 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,537 | 22.9M | 1.0M | 227.3M | $112.83 | $613.79 | $609.38 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,165 | 29.9M | 219K | 44.1M | $7.83 | $119.15 | $425.08 |
| gpt-5.6-sol-fast | 53 | 142K | 14K | 3.5M | $3.33 | $9.55 | $6.82 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **225,178** | **197.5M** | **73.0M** | **18,512.9M** | **$11,628.65** | **$61,421.04** | **$27,343.41** |

_19,294.7M total tokens processed. 95.9% cache hit rate._

_$88,764.45 total saved ($61,421.04 caching + $27,343.41 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-27 23:55 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
