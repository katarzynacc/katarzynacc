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
| Input activity (Linux) | 4.4h | 4.9h | 5.2h | ~204h* |
| Interactive human attention | 4.6h | 4.6h | 7.9h | 164.3h |
| Interactive AI generation | 2.3h | 2.3h | 5.3h | 318.8h |
| Worker-classified human attention | 0.3h | 0.3h | 1.0h | 65.6h |
| Worker/headless AI generation | 13.4h | 18.6h | 24.6h | 1408.7h |
| Additive observed work | 20.7h | 25.8h | 38.8h | 1,952.1h |
| Interactive sessions | 4 | 5 | 10 | 184 |
| Worker sessions | 198 | 439 | 1,027 | 17,048 |

_Input activity from linux-input-activity:idle-cutoff-300s; collection status: ok. Input sampling began 2026-11-04 (9.3 of 28 days sampled); earlier days are not counted. Latest sample measured: desktop input. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 135 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-5-5 | 2,638 | 5K | 878K | 166.4M | 13.3M | 92.6% | 190 | 12.5h |
| gpt-5.6-terra | 1,181 | 6.6M | 242K | 97.5M | 0 | 93.6% | 97 | 6.9h |
| gpt-5.6-sol | 832 | 3.8M | 108K | 52.7M | 0 | 93.3% | 98 | 4.0h |
| claude-sonnet-4-6 | 605 | 733 | 127K | 77.4M | 2.3M | 97.1% | 6 | 3.0h |
| claude-opus-4-6 | 570 | 774 | 102K | 38.0M | 2.5M | 93.7% | 100 | 2.3h |
| gpt-5.6-luna | 544 | 10.5M | 27K | 1.0M | 0 | 9.4% | 537 | 0.9h |
| gpt-6-luna-fast | 176 | 1.1M | 32K | 18.6M | 0 | 94.4% | 4 | 1.2h |
| gpt-5.6-sol-fast | 169 | 340K | 38K | 22.5M | 0 | 98.5% | 1 | 0.7h |
| claude-haiku-5-5 | 3 | 12 | 4K | 35K | 246K | 12.6% | 3 | 0.0h |
| nemotron-3-ultra-free | 3 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.1h |
| gemini-3.6-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.5-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **6,725** | **22.4M** | **1.5M** | **474.5M** | **18.5M** | **92%** | **1,030** | **31.5h** |

_517.1M total tokens processed. 92% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-4-6 | 207,364 | 222K | 69.3M | 20,529.9M | 607.8M | 97.1% | 5,017 | 1,143.4h |
| claude-opus-4-6 | 16,932 | 18K | 5.3M | 1,705.8M | 58.3M | 96.7% | 745 | 95.1h |
| deepseek-v4-flash-free | 15,088 | 36.8M | 3.1M | 1,278.4M | 0 | 97.2% | 199 | 47.7h |
| gpt-5.6-sol | 14,664 | 70.3M | 3.1M | 1,189.8M | 0 | 94.4% | 797 | 103.1h |
| gpt-5.6-terra | 11,124 | 68.4M | 2.3M | 850.4M | 0 | 92.6% | 1,484 | 72.3h |
| claude-sonnet-4-5 | 10,580 | 52K | 2.9M | 499.3M | 33.2M | 93.8% | 339 | 35.9h |
| gpt-5.6-luna | 7,256 | 86.2M | 422K | 80.8M | 0 | 48.4% | 6,463 | 26.0h |
| claude-sonnet-5-5 | 5,299 | 11K | 1.5M | 307.2M | 38.0M | 89.0% | 451 | 24.1h |
| claude-haiku-4-5 | 4,893 | 20K | 960K | 275.1M | 8.8M | 96.9% | 138 | 18.8h |
| gpt-5.5 | 4,643 | 13.3M | 741K | 190.8M | 0 | 93.5% | 276 | 52.1h |
| gpt-5.4 | 4,187 | 15.8M | 1.0M | 239.4M | 0 | 93.8% | 202 | 31.3h |
| gpt-5.6-sol-fast | 2,651 | 14.0M | 565K | 289.0M | 0 | 95.4% | 19 | 27.3h |
| x-preview-f-free | 1,238 | 5.5M | 296K | 172.5M | 0 | 96.9% | 7 | 12.3h |
| nemotron-3-ultra-free | 977 | 23.6M | 95K | 102.5M | 0 | 81.3% | 7 | 5.5h |
| gpt-5.4-mini | 747 | 1.8M | 108K | 37.2M | 0 | 95.2% | 28 | 3.9h |
| big-pickle | 474 | 2.1M | 90K | 39.0M | 0 | 94.8% | 4 | 2.4h |
| gpt-5.5-fast | 367 | 1.7M | 88K | 39.5M | 0 | 95.9% | 3 | 3.1h |
| claude-opus-4-8 | 357 | 708 | 367K | 69.8M | 5.5M | 92.6% | 1 | 3.6h |
| ling-3.0-flash-fin-free | 328 | 3.1M | 70K | 35.1M | 0 | 91.9% | 2 | 1.1h |
| gpt-6-luna-fast | 176 | 1.1M | 32K | 18.6M | 0 | 94.4% | 4 | 1.2h |
| north-mini-code-free | 28 | 915K | 284 | 0 | 0 | 0.0% | 2 | 0.0h |
| claude-haiku-5-5 | 3 | 12 | 4K | 35K | 246K | 12.6% | 3 | 0.0h |
| claude-sonnet-4 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gemini-3.6-flash | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.4-fast | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-6-astra | 1 | 7K | 505 | 0 | 0 | 0.0% | 1 | 0.0h |
| pool-account-management | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **309,381** | **345.3M** | **92.8M** | **27,951.0M** | **752.1M** | **96.2%** | **16,112** | **1,710.2h** |

_29,141.4M total tokens processed. 96.2% cache hit rate._
<!-- STATS-END -->

<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/katarzynacc)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-11-14 10:30 UTC by [aidevops](https://aidevops.sh) pulse._
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
