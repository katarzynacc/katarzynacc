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
| Screen time (Linux) | 24h | 108.6h | 431.5h | ~7243h* |
| Interactive human attention | 1.0h | 16.6h | 60.3h | 83.9h |
| Interactive AI generation | 0.7h | 28.0h | 178.9h | 215.8h |
| Worker-classified human attention | 0.0h | 10.7h | 17.6h | 19.5h |
| Worker/headless AI generation | 1.6h | 101.1h | 297.2h | 1049.9h |
| Additive observed work | 3.3h | 155.8h | 552.4h | 1,366.7h |
| Interactive sessions | 3 | 18 | 68 | 104 |
| Worker sessions | 239 | 1,521 | 5,348 | 10,610 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 58 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 55,258 | 60K | 21.0M | 6,711.5M | $3,215.03 | $18,121.12 | $9,314.62 |
| claude-opus-4-6 | 3,908 | 4K | 1.3M | 403.8M | $915.12 | $5,451.97 | $0.00 |
| gpt-5.6-sol | 3,765 | 18.9M | 836K | 358.5M | $323.24 | $968.22 | $707.44 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 4,047 | 22.6M | 1.0M | 255.7M | $119.43 | $690.49 | $642.62 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 311 | 1.3M | 70K | 35.4M | $27.92 | $95.70 | $62.88 |
| deepseek-v4-flash-free | 553 | 2.8M | 162K | 46.7M | $27.13 | $126.31 | $99.82 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| claude-haiku-4-5 | 2,817 | 15K | 544K | 158.9M | $21.17 | $114.42 | $264.56 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,321 | 30.4M | 224K | 45.3M | $8.00 | $122.52 | $433.70 |
| **Total** | **76,139** | **88.1M** | **26.0M** | **8,323.1M** | **$5,008.20** | **$27,273.83** | **$11,976.86** |

_8,696.7M total tokens processed. 95.7% cache hit rate._

_$39,250.68 total saved ($27,273.83 caching + $11,976.86 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,159 | 161K | 55.1M | 13,281.3M | $6,416.58 | $35,859.56 | $19,248.68 |
| claude-opus-4-6 | 11,833 | 12K | 4.0M | 1,060.6M | $2,563.92 | $14,318.63 | $0.00 |
| gpt-5.6-sol | 13,464 | 64.8M | 2.9M | 1,101.4M | $1,039.15 | $2,973.83 | $2,274.98 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.6-terra | 5,038 | 26.2M | 1.1M | 279.1M | $132.65 | $753.65 | $718.30 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| gpt-5.6-sol-fast | 311 | 1.3M | 70K | 35.4M | $27.92 | $95.70 | $62.88 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,321 | 30.4M | 224K | 45.3M | $8.00 | $122.52 | $433.70 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **226,447** | **203.8M** | **73.2M** | **18,630.7M** | **$11,699.21** | **$61,739.29** | **$27,575.70** |

_19,419.1M total tokens processed. 95.9% cache hit rate._

_$89,314.98 total saved ($61,739.29 caching + $27,575.70 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-29 17:35 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
