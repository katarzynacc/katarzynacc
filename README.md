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
| Interactive sessions | 3 | 13 | 87 | 97 |
| Worker sessions | 482 | 1,348 | 5,335 | 9,959 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 55 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,326 | 61K | 21.1M | 7,008.6M | $3,322.88 | $18,923.32 | $9,678.22 |
| claude-opus-4-6 | 3,697 | 3K | 1.2M | 374.0M | $849.92 | $5,050.27 | $0.00 |
| gpt-5.6-sol | 5,244 | 25.0M | 1.1M | 470.9M | $426.75 | $1,271.57 | $934.59 |
| gpt-5.6-terra | 3,890 | 19.7M | 902K | 197.5M | $98.31 | $533.48 | $528.26 |
| x-preview-f-free | 1,235 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| claude-haiku-4-5 | 2,858 | 16K | 551K | 160.9M | $21.49 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,902 | 28.4M | 209K | 41.5M | $7.43 | $112.29 | $403.85 |
| **Total** | **77,500** | **83.9M** | **25.8M** | **8,550.3M** | **$4,861.27** | **$26,807.53** | **$12,334.42** |

_8,917.7M total tokens processed. 95.9% cache hit rate._

_$39,141.95 total saved ($26,807.53 caching + $12,334.42 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 146,412 | 157K | 53.6M | 12,997.8M | $6,266.00 | $35,094.12 | $18,817.21 |
| claude-opus-4-6 | 11,449 | 12K | 3.8M | 1,019.8M | $2,471.16 | $13,768.19 | $0.00 |
| gpt-5.6-sol | 13,151 | 63.0M | 2.8M | 1,066.3M | $1,008.89 | $2,879.19 | $2,206.96 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,361 | 21.4M | 954K | 211.3M | $105.34 | $570.65 | $568.19 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,235 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,902 | 28.4M | 209K | 41.5M | $7.43 | $112.29 | $403.85 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **220,038** | **189.2M** | **70.9M** | **18,069.5M** | **$11,110.76** | **$59,029.37** | **$26,746.37** |

_18,822.7M total tokens processed. 96% cache hit rate._

_$85,775.74 total saved ($59,029.37 caching + $26,746.37 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-26 02:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
