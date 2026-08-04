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
| Screen time (Linux) | 23.9h | 167.7h | 564.5h | ~7349h* |
| Interactive human attention | 2.6h | 27.3h | 32.9h | 149.1h |
| Interactive AI generation | 7.4h | 41.8h | 52.1h | 134.7h |
| Worker-classified human attention | 0.4h | 3.2h | 3.2h | 28.0h |
| Worker/headless AI generation | 9.8h | 80.6h | 599.7h | 1113.6h |
| Additive observed work | 20.1h | 152.0h | 687.1h | 1,418.8h |
| Interactive sessions | 5 | 39 | 46 | 406 |
| Worker sessions | 260 | 1,602 | 4,814 | 9,838 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 68 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 100,563 | 107K | 36.6M | 7,704.7M | $3,701.50 | $20,802.70 | $11,446.27 |
| claude-opus-4-6 | 8,769 | 9K | 3.0M | 756.5M | $1,878.14 | $10,212.89 | $0.00 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| deepseek-v4-flash-free | 11,482 | 26.3M | 2.3M | 979.8M | $438.89 | $2,645.54 | $1,634.54 |
| gpt-5.4 | 4,186 | 15.8M | 1.0M | 239.4M | $122.83 | $449.01 | $476.22 |
| claude-sonnet-4-5 | 1,920 | 23K | 621K | 134.6M | $97.54 | $363.44 | $199.10 |
| claude-sonnet-4-5 | 1,849 | 4K | 464K | 73.8M | $39.59 | $199.34 | $116.55 |
| claude-haiku-4-5 | 3,945 | 15K | 764K | 220.9M | $28.23 | $159.11 | $368.32 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| gpt-5.5 | 803 | 2.4M | 133K | 30.0M | $16.32 | $81.27 | $73.40 |
| gpt-5.6-luna | 470 | 3.8M | 26K | 4.9M | $4.71 | $13.40 | $53.54 |
| north-mini-code-free | 28 | 915K | 284 | 0 | $2.82 | $0.00 | $11.00 |
| gpt-5.4-mini | 519 | 1.2M | 82K | 25.5M | $1.41 | $47.95 | $43.59 |
| **Total** | **146,814** | **108.2M** | **47.6M** | **11,044.7M** | **$7,173.29** | **$37,334.83** | **$16,310.34** |

_11,475.2M total tokens processed. 96.2% cache hit rate._

_$53,645.17 total saved ($37,334.83 caching + $16,310.34 model routing vs all-Opus)._

_Model savings are modest because ~96.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 144,699 | 154K | 54.0M | 10,062.7M | $4,923.15 | $27,169.39 | $15,322.14 |
| claude-opus-4-6 | 9,237 | 10K | 3.2M | 800.5M | $1,982.89 | $10,806.82 | $0.00 |
| deepseek-v4-flash-free | 24,207 | 56.7M | 5.3M | 1,995.7M | $917.50 | $5,388.59 | $3,399.82 |
| gpt-5.6-sol | 11,232 | 53.7M | 2.4M | 850.0M | $824.27 | $2,295.04 | $1,809.73 |
| claude-opus-4-0 | 3,096 | 29K | 851K | 244.4M | $699.24 | $3,299.56 | $0.00 |
| claude-sonnet-4-0 | 10,712 | 102K | 3.3M | 772.8M | $473.94 | $2,086.68 | $1,127.83 |
| claude-sonnet-4-5 | 16,623 | 44K | 4.1M | 668.2M | $370.47 | $1,804.25 | $1,048.90 |
| claude-sonnet-4-5 | 6,792 | 78K | 2.8M | 472.1M | $351.62 | $1,274.70 | $735.90 |
| gpt-5.5 | 12,166 | 35.8M | 2.0M | 537.5M | $265.80 | $1,451.40 | $1,200.78 |
| gpt-5.4 | 6,924 | 25.2M | 1.5M | 355.3M | $187.61 | $666.29 | $728.17 |
| claude-haiku-4-5 | 26,298 | 51K | 5.6M | 1,378.3M | $170.15 | $992.39 | $2,361.27 |
| claude-opus-4-7 | 139 | 178 | 59K | 6.3M | $22.67 | $85.69 | $0.00 |
| gpt-5.5-fast | 508 | 2.4M | 115K | 52.8M | $21.59 | $142.64 | $99.76 |
| gpt-5.6-terra | 1,048 | 3.6M | 82K | 24.1M | $17.04 | $65.15 | $78.09 |
| claude-opus-4-8 | 39 | 78 | 41K | 2.3M | $11.57 | $31.51 | $0.00 |
| gpt-5.6-luna | 470 | 3.8M | 26K | 4.9M | $4.71 | $13.40 | $53.54 |
| north-mini-code-free | 42 | 1.3M | 1K | 0 | $4.06 | $0.00 | $15.80 |
| gpt-5.4-mini | 1,253 | 5.7M | 150K | 47.8M | $3.56 | $89.69 | $124.08 |
| claude-haiku-4-5 | 4 | 12 | 106 | 14K | $0.05 | $0.01 | $0.03 |
| **Total** | **275,489** | **189.2M** | **85.9M** | **18,276.3M** | **$11,251.89** | **$57,663.18** | **$28,105.84** |

_19,048.7M total tokens processed. 95.9% cache hit rate._

_$85,769.02 total saved ($57,663.18 caching + $28,105.84 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-04 00:57 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/katarzynacc?theme=dark" />
    <img alt="katarzynacc's commit history" src="https://commit-history.com/embed/katarzynacc" />
  </picture>
</div>
