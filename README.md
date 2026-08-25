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
| Screen time (Linux) | 23.9h | 92.5h | 458h | ~7267h* |
| Interactive human attention | 6.0h | 12.9h | 68.7h | 79.5h |
| Interactive AI generation | 9.5h | 24.1h | 195.7h | 209.3h |
| Worker-classified human attention | 6.1h | 7.4h | 16.0h | 16.2h |
| Worker/headless AI generation | 40.6h | 84.3h | 303.3h | 1022.6h |
| Additive observed work | 62.2h | 128.5h | 581.9h | 1,325.6h |
| Interactive sessions | 3 | 13 | 87 | 97 |
| Worker sessions | 427 | 1,293 | 5,280 | 9,904 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 55 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 56,362 | 61K | 21.1M | 7,044.1M | $3,332.00 | $19,019.33 | $9,721.00 |
| claude-opus-4-6 | 3,660 | 3K | 1.2M | 370.7M | $842.27 | $5,005.63 | $0.00 |
| gpt-5.6-sol | 5,408 | 25.3M | 1.1M | 488.2M | $438.51 | $1,318.39 | $960.99 |
| gpt-5.6-terra | 3,717 | 19.0M | 857K | 183.4M | $93.21 | $495.38 | $500.68 |
| x-preview-f-free | 1,233 | 5.3M | 293K | 172.2M | $75.56 | $465.06 | $288.37 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| claude-haiku-4-5 | 2,858 | 16K | 551K | 160.9M | $21.49 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,797 | 27.2M | 185K | 37.5M | $7.00 | $101.47 | $383.44 |
| **Total** | **77,383** | **82.2M** | **25.8M** | **8,581.5M** | **$4,868.27** | **$26,855.97** | **$12,352.94** |

_8,946.6M total tokens processed. 95.9% cache hit rate._

_$39,208.91 total saved ($26,855.97 caching + $12,352.94 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 146,290 | 157K | 53.5M | 12,989.4M | $6,260.64 | $35,071.56 | $18,804.29 |
| claude-opus-4-6 | 11,412 | 12K | 3.8M | 1,016.5M | $2,463.51 | $13,723.54 | $0.00 |
| gpt-5.6-sol | 13,092 | 62.6M | 2.8M | 1,060.8M | $1,002.93 | $2,864.33 | $2,194.16 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,166 | 20.6M | 909K | 197.0M | $99.95 | $531.95 | $538.98 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,233 | 5.3M | 293K | 172.2M | $75.56 | $465.06 | $288.37 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 2,797 | 27.2M | 185K | 37.5M | $7.00 | $101.47 | $383.44 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **219,518** | **186.6M** | **70.7M** | **18,033.7M** | **$11,085.27** | **$58,896.96** | **$26,668.36** |

_18,783.5M total tokens processed. 96% cache hit rate._

_$85,565.32 total saved ($58,896.96 caching + $26,668.36 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-25 22:30 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
