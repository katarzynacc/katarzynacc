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
| Interactive sessions | 2 | 13 | 53 | 112 |
| Worker sessions | 197 | 1,377 | 5,061 | 11,457 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 63 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 52,963 | 57K | 19.9M | 6,168.7M | $2,946.76 | $16,655.57 | $8,601.40 |
| claude-opus-4-6 | 3,158 | 3K | 1.0M | 327.8M | $776.55 | $4,425.55 | $0.00 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| gpt-5.6-sol | 2,329 | 11.4M | 537K | 258.1M | $221.49 | $696.95 | $479.92 |
| gpt-5.6-terra | 4,825 | 32.7M | 1.2M | 310.2M | $153.97 | $837.62 | $838.41 |
| gpt-5.6-sol-fast | 1,197 | 7.1M | 281K | 131.6M | $115.39 | $355.53 | $260.43 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| deepseek-v4-flash-free | 207 | 1.6M | 65K | 17.0M | $11.21 | $46.13 | $44.26 |
| gpt-5.6-luna | 3,399 | 29.0M | 232K | 47.3M | $7.81 | $127.75 | $419.02 |
| claude-haiku-4-5 | 863 | 4K | 183K | 51.4M | $6.08 | $37.01 | $86.08 |
| **Total** | **71,100** | **93.9M** | **24.3M** | **7,619.3M** | **$4,590.42** | **$24,765.17** | **$11,180.73** |

_7,967.7M total tokens processed. 95.6% cache hit rate._

_$35,945.90 total saved ($24,765.17 caching + $11,180.73 model routing vs all-Opus)._

_Model savings are modest because ~95.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 160,313 | 172K | 58.8M | 14,248.4M | $6,849.20 | $38,470.95 | $20,629.45 |
| claude-opus-4-6 | 12,462 | 13K | 4.2M | 1,134.0M | $2,757.86 | $15,309.21 | $0.00 |
| gpt-5.6-sol | 13,561 | 65.2M | 2.9M | 1,108.1M | $1,045.76 | $2,991.99 | $2,289.65 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | $237.10 | $942.89 | $0.00 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| gpt-5.6-terra | 5,873 | 36.3M | 1.3M | 334.3M | $167.59 | $902.77 | $916.50 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-sol-fast | 1,197 | 7.1M | 281K | 131.6M | $115.39 | $355.53 | $260.43 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,869 | 32.8M | 258K | 52.2M | $8.75 | $141.16 | $472.57 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **239,596** | **222.6M** | **77.6M** | **19,836.4M** | **$12,455.54** | **$65,786.99** | **$29,405.74** |

_20,674.7M total tokens processed. 95.9% cache hit rate._

_$95,192.73 total saved ($65,786.99 caching + $29,405.74 model routing vs all-Opus)._

_Model savings are modest because ~95.9% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-09-03 04:51 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
