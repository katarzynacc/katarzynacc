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
| Screen time (Linux) | 24h | 167.9h | 671.1h | ~7448h* |
| Interactive human attention | 0.9h | 5.1h | 41.3h | 41.3h |
| Interactive AI generation | 4.1h | 33.3h | 104.6h | 104.6h |
| Worker-classified human attention | 0.1h | 0.5h | 5.3h | 5.3h |
| Worker/headless AI generation | 7.1h | 52.5h | 335.8h | 882.4h |
| Additive observed work | 12.1h | 91.5h | 486.0h | 1,032.6h |
| Interactive sessions | 1 | 11 | 61 | 61 |
| Worker sessions | 201 | 910 | 4,401 | 7,088 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 41 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 68,641 | 74K | 24.9M | 6,662.1M | $3,140.41 | $17,987.85 | $9,493.07 |
| claude-opus-4-6 | 7,336 | 8K | 2.4M | 679.1M | $1,651.94 | $9,168.45 | $0.00 |
| gpt-5.6-sol | 10,796 | 53.0M | 2.3M | 902.5M | $852.22 | $2,436.81 | $1,862.76 |
| deepseek-v4-flash-free | 6,298 | 12.5M | 1.2M | 558.9M | $240.55 | $1,509.03 | $896.86 |
| gpt-5.6-terra | 2,453 | 11.3M | 474K | 117.4M | $70.57 | $317.21 | $305.34 |
| claude-sonnet-4-5 | 838 | 10K | 258K | 62.2M | $44.60 | $168.18 | $90.41 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 1,062 | 8.2M | 84K | 25.2M | $12.27 | $68.21 | $134.33 |
| **Total** | **99,747** | **85.2M** | **32.2M** | **9,132.2M** | **$6,029.78** | **$31,745.33** | **$12,990.01** |

_9,489.8M total tokens processed. 96.2% cache hit rate._

_$44,735.34 total saved ($31,745.33 caching + $12,990.01 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 116,085 | 124K | 42.0M | 9,105.3M | $4,411.84 | $24,584.37 | $13,451.53 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,407 | 59.1M | 2.6M | 982.9M | $933.55 | $2,654.08 | $2,049.10 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 2,640 | 12.0M | 509K | 126.4M | $75.42 | $341.45 | $327.24 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,062 | 8.2M | 84K | 25.2M | $12.27 | $68.21 | $134.33 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **180,985** | **148.4M** | **57.3M** | **13,531.5M** | **$8,597.27** | **$44,673.04** | **$20,271.89** |

_14,086.9M total tokens processed. 96.1% cache hit rate._

_$64,944.93 total saved ($44,673.04 caching + $20,271.89 model routing vs all-Opus)._

_Model savings are modest because ~96.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-11 23:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
