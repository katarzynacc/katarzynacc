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
| Screen time (Linux) | 24h | 167.9h | 671.1h | ~7461h* |
| Interactive human attention | 0.9h | 5.1h | 41.3h | 41.3h |
| Interactive AI generation | 4.1h | 33.3h | 104.6h | 104.6h |
| Worker-classified human attention | 0.1h | 0.5h | 5.3h | 5.3h |
| Worker/headless AI generation | 7.1h | 52.5h | 335.8h | 882.4h |
| Additive observed work | 12.1h | 91.5h | 486.0h | 1,032.6h |
| Interactive sessions | 2 | 12 | 62 | 62 |
| Worker sessions | 395 | 1,104 | 4,595 | 7,282 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 41 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 60,776 | 66K | 22.3M | 6,085.4M | $2,916.67 | $16,430.65 | $8,645.11 |
| claude-opus-4-6 | 6,848 | 7K | 2.2M | 628.5M | $1,539.63 | $8,485.65 | $0.00 |
| gpt-5.6-sol | 9,799 | 49.4M | 2.2M | 811.5M | $783.46 | $2,191.25 | $1,700.26 |
| deepseek-v4-flash-free | 5,692 | 11.5M | 1.1M | 511.6M | $220.17 | $1,381.35 | $821.01 |
| gpt-5.6-terra | 2,950 | 13.7M | 612K | 146.0M | $86.91 | $394.38 | $376.51 |
| claude-sonnet-4-5 | 355 | 4K | 108K | 25.1M | $19.10 | $68.01 | $36.81 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 1,203 | 9.6M | 91K | 26.1M | $13.89 | $70.58 | $152.56 |
| **Total** | **89,946** | **84.5M** | **29.2M** | **8,358.9M** | **$5,597.05** | **$29,111.44** | **$11,939.50** |

_8,705.1M total tokens processed. 96% cache hit rate._

_$41,050.94 total saved ($29,111.44 caching + $11,939.50 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 116,496 | 125K | 42.2M | 9,194.3M | $4,479.46 | $24,824.68 | $13,568.89 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,522 | 59.9M | 2.6M | 989.7M | $943.31 | $2,672.32 | $2,068.51 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,137 | 14.4M | 647K | 155.0M | $91.76 | $418.62 | $398.41 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,203 | 9.6M | 91K | 26.1M | $13.89 | $70.58 | $152.56 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **182,149** | **153.0M** | **57.7M** | **13,656.8M** | **$8,692.61** | **$45,011.13** | **$20,498.05** |

_14,227.3M total tokens processed. 96% cache hit rate._

_$65,509.18 total saved ($45,011.13 caching + $20,498.05 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-12 21:04 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
