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
| Screen time (Linux) | 24h | 144h | 431.9h | ~7305h* |
| Interactive human attention | 1.0h | 10.7h | 53.1h | 90.8h |
| Interactive AI generation | 3.2h | 22.3h | 155.2h | 233.4h |
| Worker-classified human attention | 0.6h | 10.3h | 22.9h | 27.8h |
| Worker/headless AI generation | 13.2h | 82.1h | 260.8h | 1113.5h |
| Additive observed work | 17.9h | 124.9h | 490.6h | 1,463.2h |
| Interactive sessions | 3 | 14 | 54 | 113 |
| Worker sessions | 229 | 1,409 | 5,093 | 11,489 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 63 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 53,149 | 57K | 20.0M | 6,248.0M | $2,965.02 | $16,869.77 | $8,699.47 |
| claude-opus-4-6 | 3,159 | 3K | 1.0M | 327.8M | $776.85 | $4,425.55 | $0.00 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-sol | 2,329 | 11.4M | 537K | 258.1M | $221.49 | $696.95 | $479.92 |
| gpt-5.6-terra | 4,825 | 32.7M | 1.2M | 310.2M | $153.97 | $837.62 | $838.41 |
| gpt-5.6-sol-fast | 1,205 | 7.2M | 284K | 131.8M | $116.07 | $355.94 | $261.90 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| deepseek-v4-flash-free | 207 | 1.6M | 65K | 17.0M | $11.21 | $46.13 | $44.26 |
| gpt-5.6-luna | 3,422 | 29.2M | 232K | 47.4M | $7.86 | $128.13 | $421.85 |
| claude-haiku-4-5 | 863 | 4K | 183K | 51.4M | $6.08 | $37.01 | $86.08 |
| **Total** | **71,318** | **94.2M** | **24.3M** | **7,698.9M** | **$4,609.71** | **$24,980.16** | **$11,283.09** |

_8,046.0M total tokens processed. 95.7% cache hit rate._

_$36,263.26 total saved ($24,980.16 caching + $11,283.09 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 160,625 | 172K | 58.9M | 14,340.6M | $6,887.10 | $38,719.66 | $20,745.27 |
| claude-opus-4-6 | 12,463 | 13K | 4.2M | 1,134.0M | $2,758.15 | $15,309.21 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,873 | 36.3M | 1.3M | 334.3M | $167.59 | $902.77 | $916.50 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-sol-fast | 1,205 | 7.2M | 284K | 131.8M | $116.07 | $355.94 | $261.90 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,892 | 33.0M | 259K | 52.4M | $8.80 | $141.53 | $475.39 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **239,940** | **222.9M** | **77.7M** | **19,928.8M** | **$12,494.46** | **$66,036.50** | **$29,525.86** |

_20,769.9M total tokens processed. 96% cache hit rate._

_$95,562.35 total saved ($66,036.50 caching + $29,525.86 model routing vs all-Opus)._

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
_Stats auto-updated 2026-09-03 07:51 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
