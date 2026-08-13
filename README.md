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
| Screen time (Linux) | 24h | 167.9h | 671.2h | ~7474h* |
| Interactive human attention | 4.3h | 7.9h | 45.6h | 45.6h |
| Interactive AI generation | 13.8h | 40.2h | 118.5h | 118.5h |
| Worker-classified human attention | 0.6h | 0.9h | 5.8h | 5.8h |
| Worker/headless AI generation | 7.4h | 37.0h | 319.9h | 889.8h |
| Additive observed work | 26.2h | 86.1h | 488.9h | 1,058.8h |
| Interactive sessions | 7 | 8 | 67 | 67 |
| Worker sessions | 411 | 1,083 | 4,668 | 7,479 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 58,668 | 64K | 21.7M | 6,433.4M | $3,058.16 | $17,370.21 | $9,024.21 |
| claude-opus-4-6 | 4,410 | 5K | 1.5M | 419.8M | $1,112.08 | $5,668.21 | $0.00 |
| gpt-5.6-sol | 9,846 | 49.7M | 2.2M | 818.2M | $789.22 | $2,209.32 | $1,712.72 |
| deepseek-v4-flash-free | 5,402 | 10.9M | 1.0M | 487.6M | $209.63 | $1,316.63 | $781.12 |
| gpt-5.6-terra | 3,011 | 14.3M | 626K | 147.6M | $89.19 | $398.57 | $386.55 |
| gpt-5.6-luna | 1,431 | 12.4M | 127K | 30.4M | $17.92 | $82.10 | $193.61 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| claude-sonnet-4-5 | 94 | 1K | 22K | 5.5M | $3.90 | $15.00 | $8.02 |
| **Total** | **85,185** | **87.5M** | **27.7M** | **8,467.1M** | **$5,297.32** | **$27,149.64** | **$12,313.47** |

_8,821.9M total tokens processed. 96% cache hit rate._

_$39,463.11 total saved ($27,149.64 caching + $12,313.47 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 118,878 | 127K | 43.0M | 9,822.2M | $4,749.61 | $26,520.02 | $14,370.21 |
| claude-opus-4-6 | 9,532 | 10K | 3.2M | 826.1M | $2,034.90 | $11,153.06 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,198 | 15.0M | 660K | 156.5M | $94.04 | $422.81 | $408.46 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,431 | 12.4M | 127K | 30.4M | $17.92 | $82.10 | $193.61 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **185,014** | **156.7M** | **58.6M** | **14,306.6M** | **$8,999.95** | **$46,867.84** | **$21,362.93** |

_14,900.8M total tokens processed. 96% cache hit rate._

_$68,230.77 total saved ($46,867.84 caching + $21,362.93 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-13 21:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
