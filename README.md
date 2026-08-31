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
| Screen time (Linux) | 24h | 120.3h | 431.7h | ~7268h* |
| Interactive human attention | 0.6h | 15.8h | 56.1h | 86.4h |
| Interactive AI generation | 2.2h | 26.1h | 175.6h | 220.4h |
| Worker-classified human attention | 5.2h | 16.3h | 22.2h | 25.0h |
| Worker/headless AI generation | 4.6h | 101.3h | 282.5h | 1061.7h |
| Additive observed work | 12.6h | 158.8h | 534.9h | 1,391.1h |
| Interactive sessions | 2 | 16 | 64 | 105 |
| Worker sessions | 289 | 1,639 | 5,208 | 10,942 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 60 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 51,231 | 55K | 19.4M | 6,248.2M | $2,995.44 | $16,870.34 | $8,668.34 |
| claude-opus-4-6 | 3,263 | 3K | 1.1M | 332.6M | $756.46 | $4,490.45 | $0.00 |
| gpt-5.6-sol | 3,471 | 17.0M | 785K | 336.9M | $300.45 | $909.66 | $656.12 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 4,603 | 30.7M | 1.1M | 296.6M | $146.32 | $800.97 | $795.82 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 745 | 3.9M | 175K | 82.9M | $69.97 | $224.05 | $157.59 |
| deepseek-v4-flash-free | 553 | 2.8M | 162K | 46.7M | $27.13 | $126.31 | $99.82 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| claude-haiku-4-5 | 1,313 | 7K | 266K | 72.3M | $8.84 | $52.06 | $121.72 |
| gpt-5.6-luna | 3,592 | 31.1M | 243K | 49.6M | $8.28 | $133.97 | $447.54 |
| **Total** | **70,930** | **97.6M** | **24.2M** | **7,773.1M** | **$4,664.05** | **$25,190.89** | **$11,398.16** |

_8,132.6M total tokens processed. 95.6% cache hit rate._

_$36,589.05 total saved ($25,190.89 caching + $11,398.16 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,784 | 162K | 55.3M | 13,316.5M | $6,434.78 | $35,954.57 | $19,305.40 |
| claude-opus-4-6 | 11,964 | 13K | 4.0M | 1,069.9M | $2,591.62 | $14,444.15 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,651 | 34.3M | 1.2M | 320.7M | $159.95 | $866.12 | $873.91 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 745 | 3.9M | 175K | 82.9M | $69.97 | $224.05 | $157.59 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,617 | 31.3M | 244K | 49.7M | $8.33 | $134.42 | $450.30 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **228,643** | **215.8M** | **73.8M** | **18,775.6M** | **$11,821.40** | **$62,230.69** | **$27,914.00** |

_19,578.1M total tokens processed. 95.9% cache hit rate._

_$90,144.70 total saved ($62,230.69 caching + $27,914.00 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-31 08:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
