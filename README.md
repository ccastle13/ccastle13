# ccastle13

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
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
| Screen time (Linux) | 24h | 167.2h | 650.4h | ~7819h* |
| Interactive human attention | 3.0h | 32.5h | 158.4h | 504.4h |
| Interactive AI generation | 23.5h | 66.1h | 382.5h | 914.4h |
| Worker-classified human attention | 0.9h | 2.7h | 2.7h | 2.7h |
| Worker/headless AI generation | 16.6h | 76.1h | 99.1h | 192.3h |
| Additive observed work | 43.5h | 176.5h | 641.7h | 1,612.8h |
| Interactive sessions | 44 | 121 | 374 | 498 |
| Worker sessions | 118 | 531 | 1,349 | 2,432 |

_Screen time from screen-time-history:daily-observations; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 86 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| grok-4.5 | 39,370 | 302.4M | 20.6M | 3,682.3M | 0 | 92.4% | 1,374 | 360.8h |
| MiniMax-M3.1-Flash | 8,593 | 15.1M | 1.8M | 1,239.3M | 0 | 98.8% | 108 | 25.5h |
| grok-4.6 | 7,862 | 67.1M | 3.1M | 861.0M | 0 | 92.8% | 71 | 43.5h |
| grok-4.7 | 6,306 | 26.7M | 1.2M | 595.1M | 0 | 95.7% | 213 | 28.0h |
| minimax-m3.1-flash-free | 3,200 | 7.6M | 840K | 319.8M | 0 | 97.7% | 54 | 14.9h |
| grok-build-0.1 | 819 | 653K | 40K | 157.4M | 0 | 99.6% | 1 | 0.9h |
| deepseek-v4-pro | 680 | 2.1M | 170K | 95.5M | 0 | 97.8% | 7 | 2.9h |
| MiniMax-M3 | 195 | 377K | 21K | 22.3M | 0 | 98.3% | 5 | 0.6h |
| qwen3-14b-q4-k-m | 60 | 265K | 46K | 677K | 0 | 71.8% | 10 | 4.3h |
| deepseek-flash | 41 | 337K | 8K | 4.9M | 0 | 93.6% | 2 | 0.1h |
| grok-4-5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen3-14b-q4-k-m-nothink | 1 | 23K | 2 | 1 | 0 | 0.0% | 1 | 0.0h |
| qwen3-vl-30b-a3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **67,129** | **422.9M** | **27.9M** | **6,978.6M** | **0** | **94.3%** | **1,775** | **481.5h** |

_7,429.6M total tokens processed. 94.3% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 47,842 | 259.9M | 12.8M | 6,033.5M | 0 | 95.9% | 371 | 386.5h |
| grok-4.5 | 43,610 | 354.2M | 23.2M | 4,576.0M | 0 | 92.8% | 1,403 | 401.5h |
| grok-4.6 | 9,408 | 90.3M | 3.6M | 1,053.2M | 0 | 92.1% | 144 | 52.9h |
| MiniMax-M3.1-Flash | 8,593 | 15.1M | 1.8M | 1,239.3M | 0 | 98.8% | 108 | 25.5h |
| grok-4.7 | 6,313 | 26.8M | 1.2M | 595.3M | 0 | 95.7% | 215 | 28.1h |
| claude-sonnet-5 | 5,447 | 10K | 4.6M | 1,661.0M | 94.2M | 94.6% | 16 | 32.2h |
| gpt-6-astra | 4,486 | 17.6M | 1.0M | 892.6M | 0 | 98.1% | 17 | 30.7h |
| gpt-5.6-terra | 4,485 | 32.8M | 944K | 202.2M | 0 | 86.0% | 389 | 18.1h |
| deepseek-v4-flash | 3,430 | 12.8M | 971K | 329.9M | 0 | 96.2% | 152 | 7.2h |
| minimax-m3.1-flash-free | 3,200 | 7.6M | 840K | 319.8M | 0 | 97.7% | 54 | 14.9h |
| grok-build-0.1 | 2,571 | 5.5M | 367K | 367.1M | 0 | 98.5% | 4 | 8.8h |
| gpt-6-sol | 1,212 | 6.0M | 310K | 221.6M | 0 | 97.3% | 10 | 8.6h |
| claude-sonnet-4-6 | 741 | 37 | 60K | 5.9M | 1.3M | 82.1% | 4 | 1.5h |
| deepseek-v4-pro | 689 | 2.2M | 173K | 95.8M | 0 | 97.7% | 9 | 3.0h |
| gpt-5.6-luna | 503 | 4.7M | 177K | 37.1M | 0 | 88.6% | 81 | 7.3h |
| MiniMax-M3 | 195 | 377K | 21K | 22.3M | 0 | 98.3% | 5 | 0.6h |
| grok-4.3 | 173 | 4.1M | 47K | 20.9M | 0 | 83.6% | 14 | 0.5h |
| big-pickle | 155 | 853K | 188K | 11.9M | 0 | 93.3% | 4 | 1.5h |
| deepseek-flash | 69 | 526K | 22K | 9.9M | 0 | 95.0% | 3 | 0.2h |
| qwen3-14b-q4-k-m | 64 | 278K | 49K | 716K | 0 | 72.0% | 12 | 5.7h |
| gpt-6-astra-fast | 8 | 301K | 1K | 994K | 0 | 76.7% | 1 | 0.1h |
| gpt-5.6-sol-pro | 2 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.6-terra-fast | 2 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3-ultra-free | 2 | 57K | 6 | 0 | 0 | 0.0% | 2 | 0.0h |
| nemotron-3.5-lightning-free | 2 | 29K | 3 | 28K | 0 | 49.0% | 2 | 0.0h |
| grok-4-5 | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen2.5-vl-3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen3-14b-q4-k-m-nothink | 1 | 23K | 2 | 1 | 0 | 0.0% | 1 | 0.0h |
| qwen3-vl-30b-a3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **143,206** | **842.6M** | **52.6M** | **17,698.0M** | **95.5M** | **95%** | **2,859** | **1,035.3h** |

_18,688.9M total tokens processed. 95% cache hit rate._
<!-- STATS-END -->

## Projects

- **[bct2-website](https://github.com/ccastle13/bct2-website)** -- No description
<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. OpenCode & Git token-efficient AI agent automation for your app, business, and personal development. Opinionated tools, services, CLI & API stack for speed, security, and 24/7 results. Open-source first. SOTA everything. Try on your repos for money-making magic.
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ccastle13)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-10-29 10:08 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/ccastle13?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="ccastle13's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/ccastle13?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
