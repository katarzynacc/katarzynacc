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
| Screen time (Linux) | 24h | 167.6h | 647.4h | ~7407h* |
| Interactive human attention | 0.0h | 14.1h | 37.7h | 37.7h |
| Interactive AI generation | 0.0h | 41.3h | 78.2h | 78.2h |
| Worker-classified human attention | 0.0h | 3.0h | 4.9h | 4.9h |
| Worker/headless AI generation | 0.0h | 100.1h | 541.6h | 852.8h |
| Additive observed work | 0.0h | 158.4h | 661.5h | 972.7h |
| Interactive sessions | 1 | 24 | 60 | 60 |
| Worker sessions | 60 | 1,194 | 4,480 | 6,456 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 37 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 92,207 | 99K | 33.3M | 7,769.6M | $3,706.09 | $20,978.08 | $11,326.82 |
| claude-opus-4-6 | 7,750 | 8K | 2.5M | 702.7M | $1,721.44 | $9,487.77 | $0.00 |
| gpt-5.6-sol | 11,495 | 55.2M | 2.4M | 871.7M | $846.83 | $2,353.67 | $1,857.95 |
| deepseek-v4-flash-free | 9,178 | 20.3M | 1.8M | 795.3M | $350.14 | $2,147.57 | $1,308.70 |
| gpt-5.4 | 2,485 | 9.1M | 630K | 149.8M | $74.31 | $280.92 | $286.78 |
| claude-sonnet-4-5 | 1,098 | 14K | 355K | 77.7M | $56.35 | $209.88 | $114.78 |
| gpt-5.6-terra | 1,299 | 5.0M | 163K | 35.5M | $25.40 | $95.99 | $112.74 |
| claude-haiku-4-5 | 2,479 | 13K | 473K | 138.5M | $18.76 | $99.73 | $230.49 |
| gpt-5.6-luna | 597 | 4.3M | 45K | 7.8M | $5.67 | $21.13 | $64.20 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 231 | 686K | 32K | 10.2M | $0.63 | $19.19 | $19.66 |
| **Total** | **128,847** | **95.8M** | **41.9M** | **10,559.2M** | **$6,808.44** | **$35,693.94** | **$15,333.12** |

_10,968.6M total tokens processed. 96.3% cache hit rate._

_$51,027.06 total saved ($35,693.94 caching + $15,333.12 model routing vs all-Opus)._

_Model savings are modest because ~96.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 114,440 | 122K | 41.4M | 8,833.5M | $4,276.95 | $23,850.55 | $13,088.60 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 11,495 | 55.2M | 2.4M | 871.7M | $846.83 | $2,353.67 | $1,857.95 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| claude-haiku-4-5 | 4,029 | 15K | 776K | 223.7M | $28.58 | $161.09 | $373.09 |
| gpt-5.6-terra | 1,299 | 5.0M | 163K | 35.5M | $25.40 | $95.99 | $112.74 |
| gpt-5.6-luna | 597 | 4.3M | 45K | 7.8M | $5.67 | $21.13 | $64.20 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **176,515** | **133.6M** | **56.1M** | **13,034.4M** | **$8,318.37** | **$43,342.13** | **$19,423.34** |

_13,561.8M total tokens processed. 96.1% cache hit rate._

_$62,765.47 total saved ($43,342.13 caching + $19,423.34 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-08 20:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
