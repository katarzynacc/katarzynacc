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
| Interactive sessions | 3 | 4 | 63 | 63 |
| Worker sessions | 240 | 912 | 4,497 | 7,308 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 42 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 60,746 | 66K | 22.3M | 6,091.7M | $2,920.71 | $16,447.74 | $8,653.06 |
| claude-opus-4-6 | 6,778 | 7K | 2.2M | 623.6M | $1,530.67 | $8,419.24 | $0.00 |
| gpt-5.6-sol | 9,846 | 49.7M | 2.2M | 818.2M | $789.22 | $2,209.32 | $1,712.72 |
| deepseek-v4-flash-free | 5,692 | 11.5M | 1.1M | 511.6M | $220.17 | $1,381.35 | $821.01 |
| gpt-5.6-terra | 2,973 | 13.8M | 618K | 147.3M | $87.67 | $397.84 | $379.77 |
| claude-haiku-4-5 | 2,323 | 13K | 427K | 124.4M | $17.22 | $89.59 | $207.25 |
| gpt-5.6-luna | 1,297 | 11.0M | 122K | 29.7M | $16.36 | $80.34 | $176.12 |
| claude-sonnet-4-5 | 113 | 1K | 29K | 6.0M | $5.01 | $16.30 | $9.01 |
| **Total** | **89,768** | **86.3M** | **29.1M** | **8,352.8M** | **$5,587.03** | **$29,041.72** | **$11,958.95** |

_8,699.3M total tokens processed. 96% cache hit rate._

_$41,000.67 total saved ($29,041.72 caching + $11,958.95 model routing vs all-Opus)._

_Model savings are modest because ~96% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 116,655 | 125K | 42.2M | 9,218.8M | $4,490.89 | $24,890.94 | $13,601.32 |
| claude-opus-4-6 | 9,385 | 10K | 3.2M | 816.7M | $2,009.78 | $11,025.48 | $0.00 |
| gpt-5.6-sol | 12,569 | 60.2M | 2.7M | 996.4M | $949.07 | $2,690.40 | $2,080.97 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| gpt-5.6-terra | 3,160 | 14.5M | 653K | 156.3M | $92.52 | $422.08 | $401.68 |
| claude-haiku-4-5 | 4,136 | 16K | 800K | 229.4M | $29.25 | $165.23 | $382.92 |
| gpt-5.6-luna | 1,297 | 11.0M | 122K | 29.7M | $16.36 | $80.34 | $176.12 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **182,472** | **154.8M** | **57.8M** | **13,692.9M** | **$8,713.03** | **$45,108.69** | **$20,569.78** |

_14,266.2M total tokens processed. 96% cache hit rate._

_$65,678.46 total saved ($45,108.69 caching + $20,569.78 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-12 23:04 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
