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
| Worker sessions | 231 | 1,581 | 5,150 | 10,884 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 60 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 51,304 | 56K | 19.5M | 6,264.7M | $3,003.95 | $16,914.84 | $8,691.39 |
| claude-opus-4-6 | 3,227 | 3K | 1.1M | 329.7M | $746.82 | $4,451.42 | $0.00 |
| gpt-5.6-sol | 3,862 | 19.3M | 867K | 365.3M | $329.86 | $986.37 | $722.10 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 4,603 | 30.7M | 1.1M | 296.6M | $146.32 | $800.97 | $795.82 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 708 | 3.7M | 170K | 80.1M | $67.27 | $216.29 | $151.52 |
| deepseek-v4-flash-free | 553 | 2.8M | 162K | 46.7M | $27.13 | $126.31 | $99.82 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| claude-haiku-4-5 | 1,313 | 7K | 266K | 72.3M | $8.84 | $52.06 | $121.72 |
| gpt-5.6-luna | 3,571 | 31.1M | 241K | 49.1M | $8.26 | $132.63 | $447.02 |
| **Total** | **71,300** | **99.7M** | **24.3M** | **7,811.7M** | **$4,689.61** | **$25,263.97** | **$11,480.59** |

_8,173.9M total tokens processed. 95.6% cache hit rate._

_$36,744.56 total saved ($25,263.97 caching + $11,480.59 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,447 | 162K | 55.2M | 13,296.9M | $6,425.90 | $35,901.79 | $19,276.15 |
| claude-opus-4-6 | 11,928 | 12K | 4.0M | 1,067.0M | $2,581.98 | $14,405.12 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,651 | 34.3M | 1.2M | 320.7M | $159.95 | $866.12 | $873.91 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 708 | 3.7M | 170K | 80.1M | $67.27 | $216.29 | $151.52 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,571 | 31.1M | 241K | 49.1M | $8.26 | $132.63 | $447.02 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **228,187** | **215.4M** | **73.7M** | **18,749.6M** | **$11,800.11** | **$62,129.33** | **$27,875.40** |

_19,551.0M total tokens processed. 95.9% cache hit rate._

_$90,004.73 total saved ($62,129.33 caching + $27,875.40 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-31 01:57 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
