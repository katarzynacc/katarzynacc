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
| Worker sessions | 167 | 1,449 | 5,276 | 10,538 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 58 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,605 | 61K | 21.5M | 6,829.0M | $3,272.45 | $18,438.37 | $9,486.38 |
| claude-opus-4-6 | 4,058 | 4K | 1.3M | 414.5M | $940.65 | $5,595.77 | $0.00 |
| gpt-5.6-sol | 3,621 | 18.2M | 797K | 339.9M | $308.89 | $917.77 | $675.00 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-terra | 4,021 | 22.3M | 1.0M | 250.4M | $117.27 | $676.16 | $631.62 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 553 | 2.8M | 162K | 46.7M | $27.13 | $126.31 | $99.82 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| claude-haiku-4-5 | 2,856 | 16K | 551K | 160.9M | $21.46 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-sol-fast | 168 | 733K | 43K | 17.8M | $14.82 | $48.28 | $32.88 |
| gpt-5.6-luna | 3,275 | 30.4M | 223K | 45.0M | $7.98 | $121.69 | $432.59 |
| **Total** | **77,316** | **86.6M** | **26.4M** | **8,411.5M** | **$5,061.81** | **$27,623.33** | **$12,077.48** |

_8,788.2M total tokens processed. 95.7% cache hit rate._

_$39,700.81 total saved ($27,623.33 caching + $12,077.48 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 150,136 | 161K | 55.1M | 13,281.3M | $6,416.58 | $35,859.56 | $19,248.68 |
| claude-opus-4-6 | 11,827 | 12K | 4.0M | 1,060.6M | $2,563.92 | $14,318.63 | $0.00 |
| gpt-5.6-sol | 13,320 | 64.2M | 2.8M | 1,082.7M | $1,024.80 | $2,923.38 | $2,242.55 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.6-terra | 4,959 | 25.8M | 1.1M | 273.1M | $130.15 | $737.37 | $705.43 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-sol-fast | 168 | 733K | 43K | 17.8M | $14.82 | $48.28 | $32.88 |
| gpt-5.6-luna | 3,275 | 30.4M | 223K | 45.0M | $7.98 | $121.69 | $432.59 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **226,006** | **202.1M** | **73.1M** | **18,588.2M** | **$11,669.24** | **$61,624.31** | **$27,499.28** |

_19,374.8M total tokens processed. 95.9% cache hit rate._

_$89,123.58 total saved ($61,624.31 caching + $27,499.28 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-29 07:59 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
