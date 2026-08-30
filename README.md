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
| Screen time (Linux) | 24h | 108.6h | 431.7h | ~7256h* |
| Interactive human attention | 1.9h | 18.5h | 58.8h | 85.8h |
| Interactive AI generation | 2.3h | 30.3h | 178.0h | 218.2h |
| Worker-classified human attention | 0.4h | 11.1h | 17.2h | 19.8h |
| Worker/headless AI generation | 7.2h | 97.3h | 286.7h | 1057.1h |
| Additive observed work | 11.9h | 156.5h | 539.1h | 1,378.5h |
| Interactive sessions | 3 | 18 | 67 | 105 |
| Worker sessions | 338 | 1,522 | 5,248 | 10,795 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 59 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 52,003 | 56K | 19.7M | 6,379.8M | $3,057.03 | $17,225.61 | $8,843.93 |
| claude-opus-4-6 | 3,386 | 3K | 1.1M | 355.3M | $807.47 | $4,797.34 | $0.00 |
| gpt-5.6-sol | 3,862 | 19.3M | 867K | 365.3M | $329.86 | $986.37 | $722.10 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 4,603 | 30.7M | 1.1M | 296.6M | $146.32 | $800.97 | $795.82 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 623 | 3.0M | 148K | 69.3M | $57.36 | $187.14 | $128.78 |
| deepseek-v4-flash-free | 553 | 2.8M | 162K | 46.7M | $27.13 | $126.31 | $99.82 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| claude-haiku-4-5 | 1,861 | 10K | 366K | 109.9M | $14.21 | $79.18 | $182.35 |
| gpt-5.6-luna | 3,495 | 30.8M | 235K | 48.1M | $8.17 | $130.11 | $442.27 |
| **Total** | **72,545** | **98.7M** | **24.7M** | **7,978.3M** | **$4,798.71** | **$25,916.11** | **$11,666.27** |

_8,346.8M total tokens processed. 95.6% cache hit rate._

_$37,582.39 total saved ($25,916.11 caching + $11,666.27 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,159 | 161K | 55.1M | 13,281.3M | $6,416.58 | $35,859.56 | $19,248.68 |
| claude-opus-4-6 | 11,833 | 12K | 4.0M | 1,060.6M | $2,563.92 | $14,318.63 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,651 | 34.3M | 1.2M | 320.7M | $159.95 | $866.12 | $873.91 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| gpt-5.6-sol-fast | 623 | 3.0M | 148K | 69.3M | $57.36 | $187.14 | $128.78 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,495 | 30.8M | 235K | 48.1M | $8.17 | $130.11 | $442.27 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **227,643** | **214.5M** | **73.5M** | **18,715.8M** | **$11,762.73** | **$61,968.94** | **$27,820.44** |

_19,515.1M total tokens processed. 95.9% cache hit rate._

_$89,789.37 total saved ($61,968.94 caching + $27,820.44 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-30 17:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
