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
| Screen time (Linux) | 23.9h | 167.7h | 648.7h | ~7407h* |
| Interactive human attention | 0.1h | 10.9h | 37.8h | 37.8h |
| Interactive AI generation | 0.9h | 39.0h | 79.1h | 79.1h |
| Worker-classified human attention | 0.0h | 2.3h | 4.9h | 4.9h |
| Worker/headless AI generation | 9.1h | 91.4h | 450.2h | 861.8h |
| Additive observed work | 10.0h | 143.4h | 571.1h | 982.7h |
| Interactive sessions | 1 | 22 | 60 | 60 |
| Worker sessions | 134 | 983 | 4,229 | 6,530 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 90,265 | 96K | 32.6M | 7,679.1M | $3,657.25 | $20,733.60 | $11,176.04 |
| claude-opus-4-6 | 7,750 | 8K | 2.5M | 702.7M | $1,721.44 | $9,487.77 | $0.00 |
| gpt-5.6-sol | 11,864 | 56.8M | 2.5M | 912.8M | $880.15 | $2,464.77 | $1,931.59 |
| deepseek-v4-flash-free | 8,785 | 19.0M | 1.7M | 758.7M | $334.19 | $2,048.72 | $1,245.87 |
| gpt-5.4 | 1,967 | 7.4M | 516K | 127.8M | $61.81 | $239.76 | $238.16 |
| claude-sonnet-4-5 | 1,098 | 14K | 355K | 77.7M | $56.35 | $209.88 | $114.78 |
| gpt-5.6-terra | 1,450 | 6.3M | 206K | 41.6M | $31.78 | $112.38 | $138.85 |
| claude-haiku-4-5 | 2,479 | 13K | 473K | 138.5M | $18.76 | $99.73 | $230.49 |
| gpt-5.6-luna | 735 | 5.3M | 68K | 22.6M | $8.86 | $61.22 | $96.07 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 231 | 686K | 32K | 10.2M | $0.63 | $19.19 | $19.66 |
| **Total** | **126,652** | **96.8M** | **41.2M** | **10,472.2M** | **$6,774.04** | **$35,477.03** | **$15,202.51** |

_10,878.9M total tokens processed. 96.3% cache hit rate._

_$50,679.55 total saved ($35,477.03 caching + $15,202.51 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 114,440 | 122K | 41.4M | 8,833.5M | $4,276.95 | $23,850.55 | $13,088.60 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 11,864 | 56.8M | 2.5M | 912.8M | $880.15 | $2,464.77 | $1,931.59 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 1,450 | 6.3M | 206K | 41.6M | $31.78 | $112.38 | $138.85 |
| claude-haiku-4-5 | 4,029 | 15K | 776K | 223.7M | $28.58 | $161.09 | $373.09 |
| gpt-5.6-luna | 735 | 5.3M | 68K | 22.6M | $8.86 | $61.22 | $96.07 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **177,173** | **137.6M** | **56.3M** | **13,096.5M** | **$8,361.26** | **$43,509.71** | **$19,554.96** |

_13,628.1M total tokens processed. 96.1% cache hit rate._

_$63,064.67 total saved ($43,509.71 caching + $19,554.96 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-09 00:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
