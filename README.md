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
| Screen time (Linux) | 24h | 164.9h | 628.2h | ~7678h* |
| Interactive human attention | 5.5h | 50.9h | 210.3h | 469.7h |
| Interactive AI generation | 60.0h | 190.3h | 389.1h | 793.0h |
| Worker-classified human attention | 0.0h | 0.0h | 0.1h | 0.1h |
| Worker/headless AI generation | 1.7h | 8.0h | 61.6h | 114.0h |
| Additive observed work | 67.2h | 249.2h | 661.0h | 1,376.8h |
| Interactive sessions | 114 | 180 | 239 | 314 |
| Worker sessions | 60 | 303 | 1,121 | 1,860 |

_Screen time from linux-systemd-logind:session-lid-lock-state; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 77 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| grok-4.5 | 29,829 | 274.7M | 15.7M | 3,255.5M | 0 | 92.2% | 1,026 | 312.8h |
| gpt-5.6-sol | 14,621 | 86.3M | 3.6M | 1,745.1M | 0 | 95.3% | 245 | 97.6h |
| grok-4.6 | 5,663 | 55.9M | 2.3M | 606.2M | 0 | 91.5% | 66 | 34.2h |
| grok-build-0.1 | 2,430 | 5.2M | 346K | 356.6M | 0 | 98.6% | 2 | 8.6h |
| grok-4.7 | 1,901 | 9.1M | 475K | 214.1M | 0 | 95.9% | 7 | 6.2h |
| gpt-6-sol | 1,212 | 6.0M | 310K | 221.6M | 0 | 97.3% | 10 | 8.6h |
| deepseek-v4-pro | 689 | 2.2M | 173K | 95.8M | 0 | 97.7% | 9 | 3.0h |
| minimax-m3.1-flash-free | 551 | 1.3M | 205K | 58.0M | 0 | 97.7% | 10 | 2.3h |
| deepseek-v4-flash | 455 | 2.2M | 110K | 26.6M | 0 | 92.2% | 24 | 0.7h |
| grok-4.3 | 148 | 2.7M | 42K | 18.1M | 0 | 86.9% | 9 | 0.4h |
| deepseek-flash | 69 | 526K | 22K | 9.9M | 0 | 95.0% | 3 | 0.2h |
| qwen3-14b-q4-k-m | 4 | 12K | 2K | 38K | 0 | 75.5% | 2 | 1.4h |
| qwen2.5-vl-3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen3-14b-q4-k-m-nothink | 1 | 23K | 2 | 1 | 0 | 0.0% | 1 | 0.0h |
| qwen3-vl-30b-a3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **57,575** | **446.5M** | **23.4M** | **6,608.0M** | **0** | **93.7%** | **1,333** | **475.9h** |

_7,078.0M total tokens processed. 93.7% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 47,842 | 259.9M | 12.8M | 6,033.5M | 0 | 95.9% | 371 | 386.5h |
| grok-4.5 | 29,829 | 274.7M | 15.7M | 3,255.5M | 0 | 92.2% | 1,026 | 312.8h |
| grok-4.6 | 7,019 | 75.7M | 2.7M | 784.5M | 0 | 91.2% | 121 | 41.8h |
| claude-sonnet-5 | 5,447 | 10K | 4.6M | 1,661.0M | 94.2M | 94.6% | 16 | 32.2h |
| gpt-6-astra | 4,486 | 17.6M | 1.0M | 892.6M | 0 | 98.1% | 17 | 30.7h |
| gpt-5.6-terra | 4,485 | 32.8M | 944K | 202.2M | 0 | 86.0% | 389 | 18.1h |
| deepseek-v4-flash | 3,430 | 12.8M | 971K | 329.9M | 0 | 96.2% | 152 | 7.2h |
| grok-build-0.1 | 2,571 | 5.5M | 367K | 367.1M | 0 | 98.5% | 4 | 8.8h |
| grok-4.7 | 1,901 | 9.1M | 475K | 214.1M | 0 | 95.9% | 7 | 6.2h |
| gpt-6-sol | 1,212 | 6.0M | 310K | 221.6M | 0 | 97.3% | 10 | 8.6h |
| claude-sonnet-4-6 | 741 | 37 | 60K | 5.9M | 1.3M | 82.1% | 4 | 1.5h |
| deepseek-v4-pro | 689 | 2.2M | 173K | 95.8M | 0 | 97.7% | 9 | 3.0h |
| minimax-m3.1-flash-free | 551 | 1.3M | 205K | 58.0M | 0 | 97.7% | 10 | 2.3h |
| gpt-5.6-luna | 503 | 4.7M | 177K | 37.1M | 0 | 88.6% | 81 | 7.3h |
| grok-4.3 | 173 | 4.1M | 47K | 20.9M | 0 | 83.6% | 14 | 0.5h |
| big-pickle | 155 | 853K | 188K | 11.9M | 0 | 93.3% | 4 | 1.5h |
| deepseek-flash | 69 | 526K | 22K | 9.9M | 0 | 95.0% | 3 | 0.2h |
| gpt-6-astra-fast | 8 | 301K | 1K | 994K | 0 | 76.7% | 1 | 0.1h |
| qwen3-14b-q4-k-m | 4 | 12K | 2K | 38K | 0 | 75.5% | 2 | 1.4h |
| gpt-5.6-sol-pro | 2 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| gpt-5.6-terra-fast | 2 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| nemotron-3-ultra-free | 2 | 57K | 6 | 0 | 0 | 0.0% | 2 | 0.0h |
| nemotron-3.5-lightning-free | 2 | 29K | 3 | 28K | 0 | 49.0% | 2 | 0.0h |
| qwen2.5-vl-3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| qwen3-14b-q4-k-m-nothink | 1 | 23K | 2 | 1 | 0 | 0.0% | 1 | 0.0h |
| qwen3-vl-30b-a3b-q4-k-m | 1 | 0 | 0 | 0 | 0 | 0.0% | 1 | 0.0h |
| **Total** | **111,126** | **708.7M** | **40.9M** | **14,203.5M** | **95.5M** | **94.6%** | **2,109** | **870.6h** |

_15,048.8M total tokens processed. 94.6% cache hit rate._
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
_Stats auto-updated 2026-10-20 22:04 UTC by [aidevops](https://aidevops.sh) pulse._
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
