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
| Interactive sessions | 2 | 17 | 67 | 103 |
| Worker sessions | 189 | 1,471 | 5,298 | 10,560 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 58 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,288 | 61K | 21.3M | 6,808.8M | $3,261.85 | $18,384.00 | $9,454.37 |
| claude-opus-4-6 | 4,014 | 4K | 1.3M | 412.2M | $934.80 | $5,565.41 | $0.00 |
| gpt-5.6-sol | 3,764 | 18.9M | 836K | 358.5M | $323.24 | $968.22 | $707.44 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 4,031 | 22.4M | 1.0M | 251.0M | $117.61 | $677.84 | $633.41 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 553 | 2.8M | 162K | 46.7M | $27.13 | $126.31 | $99.82 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| claude-haiku-4-5 | 2,817 | 15K | 544K | 158.9M | $21.17 | $114.42 | $264.56 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-sol-fast | 168 | 733K | 43K | 17.8M | $14.82 | $48.28 | $32.88 |
| gpt-5.6-luna | 3,283 | 30.4M | 223K | 45.1M | $7.98 | $121.99 | $432.86 |
| **Total** | **77,077** | **87.3M** | **26.3M** | **8,406.5M** | **$5,059.76** | **$27,589.54** | **$12,076.56** |

_8,782.9M total tokens processed. 95.7% cache hit rate._

_$39,666.10 total saved ($27,589.54 caching + $12,076.56 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,150 | 161K | 55.1M | 13,281.3M | $6,416.58 | $35,859.56 | $19,248.68 |
| claude-opus-4-6 | 11,830 | 12K | 4.0M | 1,060.6M | $2,563.92 | $14,318.63 | $0.00 |
| gpt-5.6-sol | 13,463 | 64.8M | 2.9M | 1,101.4M | $1,039.15 | $2,973.83 | $2,274.98 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.6-terra | 4,977 | 25.9M | 1.1M | 273.8M | $130.54 | $739.36 | $707.48 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-sol-fast | 168 | 733K | 43K | 17.8M | $14.82 | $48.28 | $32.88 |
| gpt-5.6-luna | 3,283 | 30.4M | 223K | 45.1M | $7.98 | $121.99 | $432.86 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **226,192** | **202.9M** | **73.2M** | **18,607.7M** | **$11,683.98** | **$61,677.04** | **$27,534.04** |

_19,395.1M total tokens processed. 95.9% cache hit rate._

_$89,211.08 total saved ($61,677.04 caching + $27,534.04 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-29 09:59 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
