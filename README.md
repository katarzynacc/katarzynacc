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
| Interactive sessions | 4 | 5 | 64 | 64 |
| Worker sessions | 293 | 965 | 4,550 | 7,361 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 60,289 | 65K | 22.2M | 6,114.0M | $2,928.78 | $16,507.96 | $8,673.19 |
| claude-opus-4-6 | 6,506 | 7K | 2.1M | 586.0M | $1,464.37 | $7,912.23 | $0.00 |
| gpt-5.6-sol | 9,846 | 49.7M | 2.2M | 818.2M | $789.22 | $2,209.32 | $1,712.72 |
| deepseek-v4-flash-free | 5,692 | 11.5M | 1.1M | 511.6M | $220.17 | $1,381.35 | $821.01 |
| gpt-5.6-terra | 2,976 | 13.9M | 619K | 147.3M | $87.92 | $397.84 | $380.95 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 1,336 | 11.4M | 123K | 29.9M | $16.81 | $80.86 | $181.17 |
| claude-sonnet-4-5 | 112 | 1K | 28K | 6.0M | $4.56 | $16.30 | $8.99 |
| **Total** | **89,080** | **86.8M** | **28.9M** | **8,337.7M** | **$5,529.05** | **$28,595.47** | **$11,985.27** |

_8,685.1M total tokens processed. 96% cache hit rate._

_$40,580.74 total saved ($28,595.47 caching + $11,985.27 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 117,386 | 125K | 42.5M | 9,306.5M | $4,530.97 | $25,127.82 | $13,724.61 |
| claude-opus-4-6 | 9,532 | 10K | 3.2M | 826.1M | $2,034.90 | $11,153.06 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,163 | 14.6M | 654K | 156.3M | $92.77 | $422.08 | $402.86 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,336 | 11.4M | 123K | 29.9M | $16.81 | $80.86 | $181.17 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **183,392** | **155.3M** | **58.1M** | **13,790.3M** | **$8,778.93** | **$45,473.67** | **$20,699.29** |

_14,367.3M total tokens processed. 96% cache hit rate._

_$66,172.96 total saved ($45,473.67 caching + $20,699.29 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-13 06:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
