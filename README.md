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
| Screen time (Linux) | 24h | 141.5h | 431.8h | ~7293h* |
| Interactive human attention | 0.4h | 10.3h | 53.7h | 89.9h |
| Interactive AI generation | 6.8h | 21.0h | 159.0h | 230.3h |
| Worker-classified human attention | 1.3h | 11.0h | 22.4h | 27.2h |
| Worker/headless AI generation | 16.6h | 77.8h | 270.5h | 1100.3h |
| Additive observed work | 25.1h | 119.7h | 504.1h | 1,445.2h |
| Interactive sessions | 8 | 16 | 62 | 112 |
| Worker sessions | 269 | 1,487 | 5,190 | 11,368 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 62 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 54,060 | 58K | 20.3M | 6,120.2M | $2,956.83 | $16,524.77 | $8,569.01 |
| claude-opus-4-6 | 3,491 | 3K | 1.2M | 359.8M | $839.49 | $4,857.53 | $0.00 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-sol | 2,329 | 11.4M | 537K | 258.1M | $221.49 | $696.95 | $479.92 |
| gpt-5.6-terra | 4,824 | 32.7M | 1.2M | 310.2M | $153.97 | $837.62 | $838.41 |
| gpt-5.6-sol-fast | 1,182 | 6.9M | 279K | 129.7M | $113.52 | $350.25 | $256.16 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| deepseek-v4-flash-free | 207 | 1.6M | 65K | 17.0M | $11.21 | $46.13 | $44.26 |
| gpt-5.6-luna | 3,371 | 28.7M | 227K | 46.9M | $7.73 | $126.87 | $414.85 |
| claude-haiku-4-5 | 1,007 | 5K | 205K | 56.3M | $6.74 | $40.56 | $94.69 |
| **Total** | **72,630** | **93.5M** | **24.9M** | **7,605.5M** | **$4,662.14** | **$25,063.74** | **$11,148.50** |

_7,959.3M total tokens processed. 95.6% cache hit rate._

_$36,212.25 total saved ($25,063.74 caching + $11,148.50 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 158,674 | 170K | 58.2M | 13,985.6M | $6,735.39 | $37,761.29 | $20,281.89 |
| claude-opus-4-6 | 12,331 | 13K | 4.2M | 1,114.7M | $2,712.84 | $15,049.35 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,872 | 36.3M | 1.3M | 334.3M | $167.59 | $902.77 | $916.50 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-sol-fast | 1,182 | 6.9M | 279K | 129.7M | $113.52 | $350.25 | $256.16 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,800 | 32.1M | 251K | 51.7M | $8.57 | $139.79 | $462.80 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **237,741** | **221.7M** | **77.0M** | **19,551.8M** | **$12,294.66** | **$64,810.84** | **$29,044.14** |

_20,380.8M total tokens processed. 95.9% cache hit rate._

_$93,854.98 total saved ($64,810.84 caching + $29,044.14 model routing vs all-Opus)._

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
_Stats auto-updated 2026-09-02 16:06 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
