```
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   C O N T R A C T O R K E I T H                              │
│   37 years in construction. Now shipping code.               │
│                                                              │
├──────────────────────────────────────────────────────────────┤
│  PROJECT NO: 1989-∞      SCALE: NTS              REV: DAILY  │
│  DRAWN BY: CONTRACTORKEITH                       SHEET: 1/∞  │
└──────────────────────────────────────────────────────────────┘
```

[![X](https://img.shields.io/badge/@contractorkeith-000?style=flat&logo=x&logoColor=white)](https://x.com/contractorkeith)
[![Website](https://img.shields.io/badge/contractorkeith.com-2ea44f?style=flat&logo=rss&logoColor=white)](https://contractorkeith.com)
[![YouTube](https://img.shields.io/badge/YouTube-first_videos_soon-FF0000?style=flat&logo=youtube&logoColor=white)](https://youtube.com/@contractorkeith)
[![Contractor Takeoff](https://img.shields.io/badge/contractortakeoff.ai-1f6feb?style=flat)](https://contractortakeoff.ai)

**Electrician → plumber → GC → home builder → planning board → commercial fence estimator → `git push`**

I spent 37 years building things you can stand on including hundreds of buildings and developments, my own plumbing company, my own fence company, and my own home building company, managed crews, transacted hundreds of real estate deals, chaired planning boards, the works. Half of construction is managing information under deadline pressure. Turns out that's half of software too.

Now I am building the tools I always wished existed on the construction side of the table, plus a growing pile of agent tooling, MCP servers, and terminal apps along the way. **37 years in construction. 0 CS degrees. 30 public repos and counting.**

## The big build — Contractor Takeoff

**[contractortakeoff.ai](https://contractortakeoff.ai)** → *Run every bid from one command center.*

An AI-native bid management suite for specialty subcontractors: bid workspaces, integrated plan markup and measurement, and the workflow glue between them. **Local-first by design** — your plans stay on your machine, because your bid documents are nobody's training data.

|  |  |
|---|---|
| **Platform** | [contractortakeoff.ai](https://contractortakeoff.ai) — closed pilot now, public launch coming |
| **Docs** | [docs.contractortakeoff.ai](https://docs.contractortakeoff.ai) |
| **Open-source engine** | [contractor-bid](https://github.com/ContractorKeith/contractor-bid) — free, MIT-licensed, yours today |

```bash
pipx install "contractor-bid[mcp]"                 # or
brew install ContractorKeith/tap/contractor-bid
```

```
STATUS REPORT — Q3 2026
────────────────────────────────────────────────────────────
contractor takeoff platform    ██████████████░░░░░░   closed pilot → launch
plan markup + measurement      █████████░░░░░░░░░░░   framing
contractor-bid (open source)   ████████████████░░░░   v0.2.x — live now
```

This is a decade-scale build with 37 years of estimating behind it. If you're working in construction tech — building, investing, or just obsessed with dragging bid day into this decade — my DMs are open: [@contractorkeith](https://x.com/contractorkeith).

```
 /\  /\  /\  /\  /\  /\  /\  /\  /\  /\  /\  /\  /\  /\  /\ 
=||==||==||==||==||==||==||==||==||==||==||==||==||==||==||=
 ||  ||  ||  ||  ||  ||  ||  ||  ||  ||  ||  ||  ||  ||  || 
=||==||==||==||==||==||==||==||==||==||==||==||==||==||==||=
```
*Division 32 — Exterior Improvements. I estimate these for a living.*

## The sheet index

Things you can clone, run, and contribute to today. Issues and PRs welcome from tradespeople and programmers alike.

| SHEET | PROJECT | SPEC | SCOPE OF WORK |
|-------|---------|------|---------------|
| `A-101` | [contractor-bid](https://github.com/ContractorKeith/contractor-bid) | Python | The open-source engine under Contractor Takeoff. AI-ready bid workspaces for commercial subs — structure an agent can work in without losing the audit trail |
| `A-201` | [claude-architect-course](https://github.com/ContractorKeith/claude-architect-course) | Shell | Interactive course for the Claude Certified Architect exam, delivered *inside* Claude Code. Clone it, open it, say `/start` |
| `S-101` | [mcp-macos-toolkit](https://github.com/ContractorKeith/mcp-macos-toolkit) | TypeScript | Safety-first, local-first macOS MCP tools — files, Shortcuts, Homebrew, Calendar, Reminders, Ollama, MLX |
| `E-101` | [agent-observability-tui](https://github.com/ContractorKeith/agent-observability-tui) | Python | Local-first TUI for tracing, replaying, and comparing agent & MCP sessions. See what your agents actually did |
| `M-101` | [project-planner](https://github.com/ContractorKeith/project-planner) + [mvp-builder](https://github.com/ContractorKeith/mvp-builder) | Claude Code | A planning-only orchestrator and its build-mode twin. Plan the work, then work the plan |
| `P-101` | [local-job-scraper](https://github.com/ContractorKeith/local-job-scraper) | Python | Scrapes local company sites for job openings; GitHub Actions delivers a weekly report. Set-and-forget pipelines |
| `C-101` | [terminal-construction-tycoon](https://github.com/ContractorKeith/terminal-construction-tycoon) | Python | **Bid Day** — a deterministic terminal tycoon about winning work, making payroll, and running six CSI subcontractor trades |
| `T-101` | [homebrew-cli-toolbelt](https://github.com/ContractorKeith/homebrew-cli-toolbelt) | Shell | 40+ modern CLI tools for macOS in 3 tiers, with a cheatsheet for every tool |

*A = architectural · S = structural · E = electrical · M = mechanical · P = plumbing · C = civil · T = the toolbelt. Sheet numbers approximate — the architect will issue a revision.*

**Full drawing set →** [all repos](https://github.com/ContractorKeith?tab=repositories)

## Means & methods

I build like I'm still on the jobsite: figure out the end goal, find the path, get it done. AI is my crew — Claude Code, Codex, and local models — but I'm the GC. I bring the plans and the problem; nothing ships without a walkthrough.

**Speaking:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Framing:**
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=nextdotjs)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Crew:**
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000?style=flat&logo=openai)
![MCP](https://img.shields.io/badge/MCP-111?style=flat&logo=modelcontextprotocol)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat&logo=ollama)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Homebrew](https://img.shields.io/badge/Homebrew-FBB040?style=flat&logo=homebrew&logoColor=black)
