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
| Screen time (Linux) | 23.9h | 116.5h | 457.9h | ~7293h* |
| Interactive human attention | 0.6h | 12.9h | 69.0h | 80.2h |
| Interactive AI generation | 1.8h | 23.6h | 188.6h | 211.1h |
| Worker-classified human attention | 1.4h | 8.8h | 17.3h | 17.5h |
| Worker/headless AI generation | 8.9h | 85.6h | 308.9h | 1031.5h |
| Additive observed work | 12.7h | 130.6h | 581.9h | 1,338.3h |
| Interactive sessions | 5 | 15 | 88 | 101 |
| Worker sessions | 336 | 1,409 | 5,435 | 10,221 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 56 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 58,097 | 63K | 21.8M | 7,007.2M | $3,342.72 | $18,919.64 | $9,722.07 |
| claude-opus-4-6 | 3,937 | 4K | 1.3M | 397.0M | $908.09 | $5,359.62 | $0.00 |
| gpt-5.6-sol | 5,180 | 24.4M | 1.1M | 465.0M | $419.94 | $1,255.72 | $919.88 |
| gpt-5.6-terra | 3,824 | 20.1M | 925K | 203.9M | $100.81 | $550.78 | $542.01 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| deepseek-v4-flash-free | 982 | 3.4M | 249K | 84.4M | $42.38 | $228.08 | $157.30 |
| claude-opus-4-8 | 87 | 172 | 52K | 10.6M | $24.07 | $143.56 | $0.00 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| claude-haiku-4-5 | 2,856 | 16K | 551K | 160.9M | $21.46 | $115.91 | $267.99 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,046 | 29.3M | 215K | 42.8M | $7.67 | $115.72 | $416.73 |
| **Total** | **79,811** | **89.3M** | **26.7M** | **8,609.4M** | **$4,981.20** | **$27,329.22** | **$12,477.20** |

_8,986.5M total tokens processed. 95.8% cache hit rate._

_$39,806.42 total saved ($27,329.22 caching + $12,477.20 model routing vs all-Opus)._

_Model savings are modest because ~95.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 148,890 | 160K | 54.6M | 13,170.3M | $6,358.49 | $35,559.83 | $19,083.62 |
| claude-opus-4-6 | 11,689 | 12K | 4.0M | 1,042.7M | $2,529.33 | $14,077.53 | $0.00 |
| gpt-5.6-sol | 13,168 | 63.4M | 2.8M | 1,067.8M | $1,011.70 | $2,883.27 | $2,213.39 |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | $583.09 | $3,451.93 | $2,168.15 |
| claude-sonnet-4-5 | 8,013 | 20K | 1.9M | 318.8M | $173.19 | $860.83 | $499.76 |
| claude-sonnet-4-5 | 2,567 | 31K | 969K | 180.5M | $145.14 | $487.44 | $275.18 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| gpt-5.6-terra | 4,445 | 22.3M | 981K | 219.4M | $109.31 | $592.60 | $590.56 |
| gpt-5.5 | 4,642 | 13.3M | 741K | 190.8M | $96.04 | $515.24 | $433.39 |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | $76.26 | $465.87 | $291.04 |
| claude-haiku-4-5 | 4,892 | 20K | 960K | 275.1M | $34.67 | $198.11 | $459.18 |
| claude-opus-4-8 | 87 | 172 | 52K | 10.6M | $24.07 | $143.56 | $0.00 |
| nemotron-3-ultra-free | 198 | 4.6M | 13K | 25.0M | $21.95 | $67.58 | $87.00 |
| gpt-5.5-fast | 366 | 1.7M | 88K | 39.5M | $15.85 | $106.73 | $73.17 |
| gpt-5.6-luna | 3,046 | 29.3M | 215K | 42.8M | $7.67 | $115.72 | $416.73 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 746 | 1.8M | 108K | 37.2M | $2.05 | $69.77 | $63.07 |
| **Total** | **223,289** | **196.1M** | **72.0M** | **18,311.5M** | **$11,314.46** | **$60,045.03** | **$27,141.45** |

_19,080.8M total tokens processed. 96% cache hit rate._

_$87,186.48 total saved ($60,045.03 caching + $27,141.45 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-27 05:28 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
