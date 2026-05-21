# Vasiliy Uvarov

> **Six months. One author. 948,825 lines of code.**
> AI Engineer & CAIDO. I ship production agentic systems in regulated fintech — and I still write the code.

<div align="center">

[![AEO Platform](https://img.shields.io/badge/🔍_AEO_Platform-Live-00C853?style=for-the-badge)](https://www.aeo-platform.com)
[![Cosmic Copilot](https://img.shields.io/badge/✨_Cosmic_Copilot-Live-7C4DFF?style=for-the-badge)](https://www.cosmic-copilot.com)
[![AI Agents (public)](https://img.shields.io/badge/🤖_AI_Agents-Open_Source-2196F3?style=for-the-badge)](https://github.com/vasilyu1983/AI-Agents-public)

</div>

CAIDO at [Altery](https://www.altery.com) · 20 yrs TradFi + Crypto rails · Bauman MSTU (First Class) · London · UK Global Talent Visa

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vasiliyuvarov)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/vasilyu)
[![Website](https://img.shields.io/badge/ym8.co.uk-FF7139?style=flat-square&logo=safari&logoColor=white)](https://www.ym8.co.uk)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vasilyu@gmail.com)

---

## The Receipt — Last 6 Months, Solo

> Most of my work lives in private repos. Here's the verifiable telemetry.

| Repo | Code LOC | Commits | Last 90d | Stack |
|---|---:|---:|---:|---|
| cosmic-swift _(iOS)_ | 353,212 | 675 | 587 | SwiftUI · Swift · 1,004 files |
| cosmic-copilot _(web)_ | 323,249 | 857 | 427 | Next.js · TS · Supabase · Stripe · OpenAI + Anthropic |
| aeo-platform | 134,178 | 109 | 83 | Next.js · Supabase · OpenAI + Anthropic |
| prime-legacy-homes | 30,002 | 76 | 19 | Next.js · Tailwind · next-intl |
| qaccountants-platform | 23,645 | 1,176 | 67 | NestJS monorepo · Prisma |
| cosmic-landing | 40,828 | 122 | 48 | Next.js · next-intl |
| aeo-landing | 24,040 | 11 | 11 | Next.js · Tailwind |
| qaccountants | 17,808 | 101 | 74 | Next.js · Supabase · PostHog |
| altery-requirements-hub | 1,863 | 109 | 108 | Markdown / docs hub |
| **Total** | **948,825** | **3,236** | **1,424** | One author on every repo |

**That's ~16 commits/day, solo, while running a full-time C-level job.** Methodology: `find + wc -l` excluding `node_modules`, `.next`, `Pods`, `DerivedData`, `build`, `dist`, lockfiles. Read access on request for recruiters and serious inbound.

---

## Live Products (Built and Run Solo)

🔍 **[AEO Platform](https://www.aeo-platform.com)** — AI-search-visibility engine. Queries Google AI Overviews, ChatGPT, Perplexity, and Claude. Detects hallucinations, citation drift, and source-attribution gaps. _Paying users. 134K LOC._

✨ **[Cosmic Copilot](https://www.cosmic-copilot.com)** — Chart-accurate AI astrology. **VSOP87 ephemeris at ±0.1° precision.** 14 languages (~201K words via parallel agents). Native iOS + web, same product, ~676K LOC combined.

🌐 **[YM8](https://www.ym8.co.uk)** — Personal site + AI agents showcase.

🏠 **Prime Legacy Homes** — London residential real-estate platform.

---

## Open Source — AI Agents Library

**[vasilyu1983/AI-Agents-public](https://github.com/vasilyu1983/AI-Agents-public)** — public slice of a **192-skill production library across 14 domains** with **6-router orchestration**. Skills drop into `.claude/skills/` or `.codex/skills/`. Follows the [Agent Skills spec](https://agentskills.io/specification).

Notable families:
- **`ai-coding-agents-*` (12 skills)** — sessions, sandbox, permissions, plugins, observability/evals, terminal UI, remote runtime, command runtime, provider runtime, tools, tasks, release/distribution. Patterns for building durable coding agents.
- **`agents-swarm-orchestration`** — dependency-aware parallel subagents with verifier passes. Used in live operation: **493 sub-agent dispatches, 131 parallel overlaps in a single month**, 73% goal-achievement.
- **`foundations-game-theory` + `foundations-decision-theory`** — agent design primitives. Escalation as Stackelberg games, verifier-builder pairs as repeated games, tool selection as bounded-rational decision under uncertainty.

---

## Altery — 30 Production Agents Across 8 Departments

CAIDO at [Altery](https://www.altery.com) (UK EMI / FinTech). Built and operate **30 production agents** spanning compliance, ops, customer workflows, engineering, and data.

🦅 **Hawkeye** — AML/CTF horizon scanning, UK + EU-CY jurisdictions
📋 **RegLens** — Regulatory policy review with gap tables + audit-ready remediation
🔍 **KYB Translator** — Multi-language KYB doc translation with UBO extraction
🎯 **KYB Analyst** — AML/CFT risk assessments for business onboarding
📈 **Metabase Buddy** — Plain English → SQL/MBQL, dashboards in minutes
🔒 **Policy Reviewer** — Forensic review with verbatim quotes and regulatory citations
🛠️ **SmartDeploy · Customer Support · Mobile App Updates · Tech Writer · JD Assistant · DPIA · BPAT · Expansion Scanner · Marketing Researcher** _+ 15 more_

Underneath: a **135-repo coordination layer** cataloguing 581 API routes across 43 services, 545 documented regulatory gaps across 12 domains, README coverage 123/135, AGENTS.md 17/135.

---

## Stack — Daily, Production

**Agents & AI:** Claude Code CLI · Codex CLI · Cursor · v0 · custom MCP servers · OpenAI / Anthropic / Gemini SDKs · RAG · prompt caching · structured outputs · tool use · evals
**Frontend:** Next.js · React · TypeScript · SwiftUI · Tailwind · Radix · React Native · Expo
**Backend:** Node · NestJS · Python · Prisma · C# / .NET (origin stack, still ship)
**Data & infra:** PostgreSQL · Supabase · Firebase · Redis · Vercel · AWS S3
**Payments & analytics:** Stripe · PostHog · Resend
**Web3:** Solana · Ethereum · Wagmi · Viem · Jupiter DEX
**Testing:** Playwright · Vitest · Jest
**Fintech depth:** KYC/AML/KYB/KYT · Travel Rule · MiCA · DFSA · Visa/UnionPay Principal Memberships · multi-currency card issuing · crypto rails

---

## Background

🎓 MSc Computer Engineering — **Bauman Moscow State Technical University** (First Class) · BSc Finance (First Class)
💼 20+ years banking tech: Otkritie, Sberbank, VTB, Moscow Exchange, ECOMMPAY — £100M+ IT portfolios, 230+ FTE orgs
🛠️ Production C#/.NET at age 20 — HotSOS hotel CRM, 1,000+ properties worldwide
🌍 London · UK Global Talent Visa · Open to relocation for the right problem

---

> **Philosophy:** Ship fast, comply hard. Re-architect signal, not noise.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vasili-yuvarov)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/vasilyu)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vasilyu@gmail.com)

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=vasilyu1983&color=blueviolet&style=flat-square&label=Profile+Views)

</div>

<details>
<summary>Why the receipt matters</summary>

In 2026 everyone claims they "use AI to code." Most can't show the receipt. I run Claude Code and Codex at production intensity daily and the github telemetry above is the externally verifiable artifact: 9 separate repos, 3,236 commits, single author on every commit, ~16/day average.

The point isn't the volume — it's that a senior operator with a C-level day job can still ship as if engineering is the title. That's the "AI-augmented operator" archetype, and I think it's underrated for the next 24 months of agentic AI.

Numbers verifiable on request. Repo read-access available for serious inbound (recruiters, founders, technical partners).

</details>
