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
| Screen time (Linux) | 24h | 120.5h | 344.4h | ~7136h* |
| Interactive human attention | 1.2h | 3.9h | 33.3h | 158.9h |
| Interactive AI generation | 0.8h | 3.0h | 32.4h | 315.9h |
| Worker-classified human attention | 0.0h | 3.9h | 27.4h | 65.0h |
| Worker/headless AI generation | 0.0h | 5.2h | 109.9h | 1384.8h |
| Additive observed work | 2.0h | 15.2h | 200.7h | 1,919.2h |
| Interactive sessions | 2 | 11 | 47 | 176 |
| Worker sessions | 53 | 326 | 2,199 | 16,112 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 109 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 16,916 | 18K | 3.2M | 2,111.2M | 55.5M | 97.4% | 349 | 83.9h |
| claude-opus-4-6 | 3,494 | 3K | 824K | 424.6M | 12.8M | 97.1% | 141 | 20.2h |
| claude-sonnet-5-5 | 2,807 | 6K | 750K | 147.7M | 26.2M | 84.9% | 298 | 12.2h |
| gpt-5.6-terra | 2,638 | 17.2M | 545K | 260.0M | 0 | 93.8% | 138 | 15.8h |
| gpt-5.6-luna | 1,349 | 22.2M | 75K | 13.7M | 0 | 38.2% | 1,209 | 3.4h |
| nemotron-3-ultra-free | 608 | 15.5M | 67K | 62.1M | 0 | 80.0% | 5 | 3.2h |
| gpt-5.6-sol-fast | 588 | 2.2M | 114K | 63.7M | 0 | 96.6% | 8 | 3.3h |
| big-pickle | 474 | 2.1M | 90K | 39.0M | 0 | 94.8% | 4 | 2.4h |
| gpt-5.6-sol | 272 | 1.2M | 47K | 28.9M | 0 | 95.9% | 9 | 1.8h |
| gpt-6-luna-fast | 105 | 510K | 14K | 10.2M | 0 | 95.2% | 2 | 0.8h |
| claude-haiku-4-5 | 1 | 3 | 425 | 0 | 26K | 0.0% | 1 | 0.0h |
| gemini-3.6-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4-mini | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.5-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-6-astra | 1 | 7K | 505 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **29,259** | **61.1M** | **5.7M** | **3,161.6M** | **94.6M** | **95.3%** | **2,146** | **146.9h** |

_3,323.2M total tokens processed. 95.3% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 207,006 | 222K | 69.2M | 20,493.2M | 605.7M | 97.1% | 5,012 | 1,141.1h |
| claude-opus-4-6 | 16,727 | 18K | 5.3M | 1,692.2M | 57.1M | 96.7% | 697 | 94.5h |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | 0 | 97.2% | 199 | 47.7h |
| gpt-5.6-sol | 13,833 | 66.4M | 2.9M | 1,137.0M | 0 | 94.5% | 700 | 99.1h |
| claude-sonnet-4-5 | 10,580 | 52K | 2.9M | 499.3M | 33.2M | 93.8% | 339 | 35.9h |
| gpt-5.6-terra | 9,945 | 61.7M | 2.1M | 752.9M | 0 | 92.4% | 1,390 | 65.4h |
| gpt-5.6-luna | 6,773 | 76.8M | 398K | 79.7M | 0 | 50.9% | 5,981 | 25.2h |
| claude-haiku-4-5 | 4,893 | 20K | 960K | 275.1M | 8.8M | 96.9% | 138 | 18.8h |
| gpt-5.5 | 4,643 | 13.3M | 741K | 190.8M | 0 | 93.5% | 276 | 52.1h |
| gpt-5.4 | 4,187 | 15.8M | 1.0M | 239.4M | 0 | 93.8% | 202 | 31.3h |
| claude-sonnet-5-5 | 2,807 | 6K | 750K | 147.7M | 26.2M | 84.9% | 298 | 12.2h |
| gpt-5.6-sol-fast | 2,651 | 14.0M | 565K | 289.0M | 0 | 95.4% | 19 | 27.3h |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | 0 | 96.9% | 7 | 12.3h |
| nemotron-3-ultra-free | 977 | 23.6M | 95K | 102.5M | 0 | 81.3% | 7 | 5.5h |
| gpt-5.4-mini | 747 | 1.8M | 108K | 37.2M | 0 | 95.2% | 28 | 3.9h |
| big-pickle | 474 | 2.1M | 90K | 39.0M | 0 | 94.8% | 4 | 2.4h |
| gpt-5.5-fast | 367 | 1.7M | 88K | 39.5M | 0 | 95.9% | 3 | 3.1h |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | 5.5M | 92.6% | 1 | 3.6h |
| ling-3.0-flash-fin-free | 328 | 3.1M | 70K | 35.1M | 0 | 91.9% | 2 | 1.1h |
| gpt-6-luna-fast | 105 | 510K | 14K | 10.2M | 0 | 95.2% | 2 | 0.8h |
| north-mini-code-free | 28 | 915K | 284 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-sonnet-4 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gemini-3.6-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-6-astra | 1 | 7K | 505 | 0 | 0 | 0.0% | 1 | 0.0h |
| pool-account-management | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **303,759** | **324.9M** | **91.4M** | **27,581.3M** | **736.7M** | **96.3%** | **15,232** | **1,683.3h** |

_28,734.4M total tokens processed. 96.3% cache hit rate._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-10-19 20:02 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/katarzynacc?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="katarzynacc's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/katarzynacc?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
