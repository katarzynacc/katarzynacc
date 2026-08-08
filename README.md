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
| Worker sessions | 118 | 967 | 4,213 | 6,514 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 38 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 91,680 | 98K | 33.1M | 7,746.5M | $3,693.48 | $20,915.82 | $11,287.50 |
| claude-opus-4-6 | 7,750 | 8K | 2.5M | 702.7M | $1,721.44 | $9,487.77 | $0.00 |
| gpt-5.6-sol | 11,864 | 56.8M | 2.5M | 912.8M | $880.15 | $2,464.77 | $1,931.59 |
| deepseek-v4-flash-free | 8,946 | 19.3M | 1.8M | 776.5M | $341.02 | $2,096.63 | $1,272.24 |
| gpt-5.4 | 2,392 | 8.7M | 612K | 146.5M | $71.87 | $274.80 | $276.82 |
| claude-sonnet-4-5 | 1,098 | 14K | 355K | 77.7M | $56.35 | $209.88 | $114.78 |
| gpt-5.6-terra | 1,429 | 6.2M | 202K | 41.3M | $31.17 | $111.66 | $136.18 |
| claude-haiku-4-5 | 2,479 | 13K | 473K | 138.5M | $18.76 | $99.73 | $230.49 |
| gpt-5.6-luna | 728 | 5.3M | 67K | 22.6M | $8.80 | $61.07 | $95.39 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 231 | 686K | 32K | 10.2M | $0.63 | $19.19 | $19.66 |
| **Total** | **128,625** | **98.1M** | **41.8M** | **10,575.8M** | **$6,826.49** | **$35,741.32** | **$15,375.65** |

_10,986.7M total tokens processed. 96.3% cache hit rate._

_$51,116.97 total saved ($35,741.32 caching + $15,375.65 model routing vs all-Opus)._

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
| gpt-5.6-terra | 1,429 | 6.2M | 202K | 41.3M | $31.17 | $111.66 | $136.18 |
| claude-haiku-4-5 | 4,029 | 15K | 776K | 223.7M | $28.58 | $161.09 | $373.09 |
| gpt-5.6-luna | 728 | 5.3M | 67K | 22.6M | $8.80 | $61.07 | $95.39 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **177,145** | **137.4M** | **56.3M** | **13,096.1M** | **$8,360.59** | **$43,508.83** | **$19,551.61** |

_13,627.5M total tokens processed. 96.1% cache hit rate._

_$63,060.44 total saved ($43,508.83 caching + $19,551.61 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-08 22:01 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
