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
| Interactive sessions | 5 | 15 | 89 | 99 |
| Worker sessions | 594 | 1,459 | 5,446 | 10,070 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 55 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,139 | 61K | 21.0M | 6,971.5M | $3,306.31 | $18,823.25 | $9,629.83 |
| claude-opus-4-6 | 3,699 | 3K | 1.2M | 374.0M | $849.92 | $5,050.27 | $0.00 |
| gpt-5.6-sol | 5,184 | 24.4M | 1.1M | 465.1M | $420.02 | $1,255.79 | $920.07 |
| gpt-5.6-terra | 3,888 | 20.3M | 927K | 204.7M | $101.45 | $552.75 | $545.77 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| claude-haiku-4-5 | 2,857 | 16K | 551K | 160.9M | $21.48 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,990 | 29.0M | 213K | 42.3M | $7.59 | $114.32 | $411.97 |
| **Total** | **77,343** | **84.6M** | **25.7M** | **8,515.3M** | **$4,841.26** | **$26,712.98** | **$12,297.14** |

_8,882.1M total tokens processed. 95.9% cache hit rate._

_$39,010.11 total saved ($26,712.98 caching + $12,297.14 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 146,431 | 157K | 53.6M | 12,997.8M | $6,266.00 | $35,094.12 | $18,817.21 |
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
| gpt-5.6-luna | 2,990 | 29.0M | 213K | 42.3M | $7.59 | $114.32 | $411.97 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **220,251** | **191.0M** | **70.9M** | **18,079.9M** | **$11,117.70** | **$59,057.43** | **$26,783.28** |

_18,835.0M total tokens processed. 96% cache hit rate._

_$85,840.71 total saved ($59,057.43 caching + $26,783.28 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-26 18:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
