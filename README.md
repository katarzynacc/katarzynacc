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
| Screen time (Linux) | 23.9h | 167.9h | 431.8h | ~7317h* |
| Interactive human attention | 1.8h | 9.7h | 54.9h | 92.6h |
| Interactive AI generation | 4.8h | 23.1h | 160.0h | 238.2h |
| Worker-classified human attention | 3.5h | 11.8h | 26.4h | 31.3h |
| Worker/headless AI generation | 12.6h | 77.8h | 273.3h | 1126.1h |
| Additive observed work | 22.6h | 122.5h | 513.2h | 1,485.8h |
| Interactive sessions | 2 | 12 | 54 | 113 |
| Worker sessions | 296 | 1,309 | 5,283 | 11,679 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 64 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 50,296 | 54K | 18.9M | 5,964.1M | $2,826.37 | $16,103.08 | $8,292.69 |
| claude-opus-4-6 | 3,293 | 3K | 1.0M | 370.2M | $877.71 | $4,998.82 | $0.00 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-sol | 2,329 | 11.4M | 537K | 258.1M | $221.49 | $696.95 | $479.92 |
| gpt-5.6-terra | 4,825 | 32.7M | 1.2M | 310.2M | $153.97 | $837.62 | $838.41 |
| gpt-5.6-sol-fast | 1,340 | 8.5M | 307K | 148.0M | $132.03 | $399.82 | $298.81 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,546 | 30.4M | 237K | 47.9M | $8.14 | $129.47 | $437.76 |
| claude-haiku-4-5 | 863 | 4K | 183K | 51.4M | $6.08 | $37.01 | $86.08 |
| deepseek-v4-flash-free | 11 | 99K | 1K | 117K | $0.36 | $0.32 | $1.43 |
| **Total** | **68,662** | **95.3M** | **23.2M** | **7,457.2M** | **$4,577.31** | **$24,786.17** | **$10,886.31** |

_7,796.0M total tokens processed. 95.7% cache hit rate._

_$35,672.48 total saved ($24,786.17 caching + $10,886.31 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 161,935 | 174K | 59.3M | 14,503.6M | $6,959.67 | $39,159.97 | $20,965.10 |
| claude-opus-4-6 | 12,667 | 13K | 4.3M | 1,185.7M | $2,883.13 | $16,007.54 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,873 | 36.3M | 1.3M | 334.3M | $167.59 | $902.77 | $916.50 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.6-sol-fast | 1,340 | 8.5M | 307K | 148.0M | $132.03 | $399.82 | $298.81 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 4,016 | 34.3M | 263K | 52.9M | $9.09 | $142.88 | $491.31 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **241,713** | **225.5M** | **78.1M** | **20,160.3M** | **$12,708.26** | **$67,220.35** | **$29,798.51** |

_21,011.2M total tokens processed. 96% cache hit rate._

_$97,018.86 total saved ($67,220.35 caching + $29,798.51 model routing vs all-Opus)._

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
_Stats auto-updated 2026-09-04 08:45 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
