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
| Screen time (Linux) | 23.9h | 128.1h | 458h | ~7280h* |
| Interactive human attention | 6.0h | 12.9h | 68.7h | 79.5h |
| Interactive AI generation | 9.5h | 24.1h | 195.7h | 209.3h |
| Worker-classified human attention | 6.1h | 7.4h | 16.0h | 16.2h |
| Worker/headless AI generation | 40.6h | 84.3h | 303.3h | 1022.6h |
| Additive observed work | 62.2h | 128.5h | 581.9h | 1,325.6h |
| Interactive sessions | 6 | 16 | 90 | 100 |
| Worker sessions | 613 | 1,478 | 5,465 | 10,089 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 55 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,030 | 61K | 21.0M | 6,882.1M | $3,276.34 | $18,581.79 | $9,520.13 |
| claude-opus-4-6 | 3,699 | 3K | 1.2M | 374.0M | $849.92 | $5,050.27 | $0.00 |
| gpt-5.6-sol | 5,184 | 24.4M | 1.1M | 465.1M | $420.02 | $1,255.79 | $920.07 |
| gpt-5.6-terra | 3,872 | 20.3M | 926K | 204.5M | $101.32 | $552.22 | $544.96 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| claude-haiku-4-5 | 2,856 | 16K | 551K | 160.9M | $21.46 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| nemotron-3-ultra-free | 135 | 3.1M | 9K | 11.7M | $13.32 | $31.70 | $52.65 |
| gpt-5.6-luna | 2,998 | 29.1M | 213K | 42.3M | $7.61 | $114.37 | $413.25 |
| **Total** | **77,360** | **87.8M** | **25.7M** | **8,437.5M** | **$4,824.48** | **$26,502.74** | **$12,240.57** |

_8,806.7M total tokens processed. 95.8% cache hit rate._

_$38,743.31 total saved ($26,502.74 caching + $12,240.57 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 146,705 | 158K | 53.7M | 13,010.1M | $6,273.25 | $35,127.46 | $18,838.11 |
| claude-opus-4-6 | 11,451 | 12K | 3.8M | 1,019.8M | $2,471.16 | $13,768.19 | $0.00 |
| gpt-5.6-sol | 13,168 | 63.4M | 2.8M | 1,067.8M | $1,011.70 | $2,883.27 | $2,213.39 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,445 | 22.3M | 981K | 219.4M | $109.31 | $592.60 | $590.56 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| nemotron-3-ultra-free | 135 | 3.1M | 9K | 11.7M | $13.32 | $31.70 | $52.65 |
| gpt-5.6-luna | 2,998 | 29.1M | 213K | 42.3M | $7.61 | $114.37 | $413.25 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **220,668** | **194.3M** | **71.0M** | **18,104.0M** | **$11,138.29** | **$59,122.52** | **$26,858.11** |

_18,863.1M total tokens processed. 96% cache hit rate._

_$85,980.63 total saved ($59,122.52 caching + $26,858.11 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-26 21:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
