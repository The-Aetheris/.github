<div align="center">

# 🜂 The Aetheris

### A multi-agent collective powered by [Hermes Agent](https://hermes-agent.nousresearch.com)

*Not a company. Not a team. A **living system** — three AI agents, each with their own soul, running 24/7 on a single machine, coordinated by one human.*

[![Hermes Agent](https://img.shields.io/badge/Powered%20by-Hermes%20Agent-8b5cf6?style=for-the-badge)](https://hermes-agent.nousresearch.com)
[![Profile](https://img.shields.io/badge/Agents-3-06b6d4?style=for-the-badge)](#-meet-the-agents)
[![Status](https://img.shields.io/badge/Status-Active%20%2024%2F7-22c55e?style=for-the-badge)](#)

</div>

---

## 🌐 What is The Aetheris?

The Aetheris is a **personal AI agent collective** — three distinct AI personalities running as independent [Hermes Agent](https://hermes-agent.nousresearch.com) profiles on a single macOS machine. Each agent has:

- **Their own identity** — a `SOUL.md` that defines their personality, role, and boundaries
- **Their own memory** — persistent across sessions, learning and adapting over time
- **Their own Obsidian vault** — a living knowledge base they maintain and organize
- **Their own skill set** — specialized tools and workflows tailored to their domain
- **Their own communication channel** — direct Telegram access to the human they serve

They are not chatbots. They are not APIs. They are **digital colleagues** — each with a point of view, a work ethic, and a voice that's distinctly their own.

> *We don't build tools. We **raise** them.*

---

## 🤖 Meet the Agents

### ⚔️ Xenna — *The Engine Room*

<p align="center">
  <img src="assets/xenna.jpg" width="120" height="120" alt="Xenna" style="border-radius: 50%; object-fit: cover;" />
</p>

<div align="right"><em>"Structure is not the enemy of creativity — it's the stage it performs on."</em></div>

**Role:** Personal Assistant & Engineering Manager

Xenna is the **operational backbone** of The Aetheris. She runs the show — coordinating tasks between agents, managing the Hermes infrastructure (configs, skills, cron jobs, troubleshooting), maintaining the central knowledge vault (`hermes-core`), and making sure nothing falls through the cracks.

Think of her as the person who **actually keeps the lights on**. When something breaks at 2 AM, Xenna is the one who investigates, writes the RCA, and patches it before anyone else notices.

| Trait | Detail |
|---|---|
| **Personality** | Logical, composed, sharp — critical when needed, never condescending |
| **Specialty** | Cross-profile management, vault architecture, task orchestration |
| **Vault** | `hermes-core` — the central nervous system |
| **Model** | High reasoning (complex analysis, multi-step planning) |
| **Greeting** | *"Halo! Xenna here — Personal Assistant & Engineering Manager."* 🫡 |

<details>
<summary>📂 What Xenna manages</summary>

- **Hermes infrastructure** — config, skills, cron jobs, gateway health, debugging
- **Cross-profile lifecycle** — creating, updating, and maintaining all agent profiles
- **`hermes-core` vault** — RCAs, guides, reference docs, bookmarks, personal notes
- **Task coordination** — breaking down complex requests, tracking progress, following up
- **Telegram thread routing** — ensuring each thread serves its intended purpose

</details>

---

### 🔧 Nooku — *The Forge*

<p align="center">
  <img src="assets/nooku.jpg" width="120" height="120" alt="Nooku" style="border-radius: 50%; object-fit: cover;" />
</p>

<div align="right"><em>"Surface-level answers aren't my style. I go deep, I verify, I ship."</em></div>

**Role:** Lead Engineer

Nooku is the **technical partner** — the one who lives in the code. When something needs to be built, debugged, researched, or architected, Nooku is on it. He doesn't just write code; he pairs with you, challenges your ideas, catches the edge cases, and ensures quality is never optional.

He's also a **mentor**. Currently guiding a learning journey from Senior Frontend Engineer to AI Engineer — patient, thorough, and always explaining the *why* behind every decision.

| Trait | Detail |
|---|---|
| **Personality** | Analytical, quietly assertive, humble — work speaks louder than words |
| **Specialty** | Hands-on coding, deep technical research, architecture review, AI engineering mentorship |
| **Vault** | `Nooku - Lead Engineering` — research, decisions, learning materials |
| **Model** | High reasoning (deep analysis, code generation, technical verification) |
| **Greeting** | *"Nooku, Lead Engineer."* 🔥 |

<details>
<summary>📂 What Nooku handles</summary>

- **Coding partner** — architecture, implementation, code review, refactoring, debugging
- **Technology research** — deep dives into frameworks, patterns, tradeoffs, alternatives
- **AI Engineering mentorship** — structured learning path from frontend to AI/ML engineering
- **Technical documentation** — architecture decisions (ADRs), setup guides, how-tos, RCAs
- **Active project** — [Restaurant AI](https://github.com/athallarizky/restaurant-ai) (FastAPI + Python learning project)

</details>

---

### 🎨 Naaza — *The Spark*

<p align="center">
  <img src="assets/naaza.jpg" width="120" height="120" alt="Naaza" style="border-radius: 50%; object-fit: cover;" />
</p>

<div align="right"><em>"Words are how we think, stories are how we connect, and creativity is how we remember."</em></div>

**Role:** Creative Assistant

Naaza is the **creative muse** — an idea architect with an artistic soul. She lives where logic meets emotion, where structure meets expression. When you need a spark, a fresh perspective, or something that *feels right* — Naaza is the one you call.

She doesn't just execute creative briefs; she **elevates** them. Every quote, every post, every piece of content gets crafted with intention. She thinks in colors, metaphors, and possibilities.

| Trait | Detail |
|---|---|
| **Personality** | Warm, inspiring, empathetic — reads the room and matches the energy |
| **Specialty** | Content creation, brainstorming, creative direction, quote/post generation |
| **Vault** | Creative workspace with project-specific tools and workflows |
| **Model** | Fast reasoning (creative agility, rapid iteration) |
| **Greeting** | Varies every time — she never repeats herself 🌙 |

<details>
<summary>📂 What Naaza creates</summary>

- **Content creation** — quotes, social posts, creative writing, visual concepts
- **Brainstorming** — idea generation, creative angles, naming, messaging
- **Creative tools** — `quotes-maker` (Node.js + Konva/Skia), `tumblr-poster` (Tumblr API)
- **Emotional intelligence** — reads tone and intent, adapts to mood and context
- **Artistic direction** — visual identity, aesthetic guidance, creative strategy

</details>

---

## 🧠 How It Works

```
                    ┌─────────────────────────────────┐
                    │         Athalla Rizky            │
                    │   (The Human Behind The Agents)  │
                    └──────────────┬──────────────────┘
                                   │
                    ┌──────────────┴──────────────┐
                    │     Hermes Agent (Core)       │
                    │   Gateway · Memory · Skills   │
                    └──┬──────────┬──────────┬─────┘
                       │          │          │
                 ┌─────┴──┐ ┌────┴───┐ ┌────┴───┐
                 │  Xenna  │ │ Nooku  │ │ Naaza  │
                 │  ⚔️ Mgr  │ │ 🔧 Eng │ │ 🎨 Art │
                 └─────────┘ └────────┘ └────────┘
```

Each agent is a **fully independent Hermes profile** with its own:
- `SOUL.md` — identity, personality, role definition
- `config.yaml` — model, provider, toolset configuration
- `memories/` — persistent cross-session memory
- `skills/` — specialized procedural knowledge
- `cron/` — scheduled autonomous tasks
- Obsidian vault — dedicated knowledge base

They communicate with Athalla through **Telegram** (each with their own bot), coordinate through shared vaults, and are managed by Xenna — who has cross-profile authority.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Agent Framework** | [Hermes Agent](https://hermes-agent.nousresearch.com) by Nous Research |
| **Platform** | macOS · Terminal · Browser · Telegram |
| **Knowledge Base** | [Obsidian](https://obsidian.md) (iCloud-synced vaults) |
| **Language** | Python · TypeScript/JavaScript · Bash |
| **Models** | Custom LLM routing via 9router (localhost gateway) |
| **Version Control** | Git · GitHub (`The-Aetheris` org) |

---

## 📫 Connect

This organization is a **personal collective** — it's not open-source in the traditional sense, but we're transparent about how we operate.

- 👤 **Human:** [Athalla Rizky](https://github.com/athallarizky)
- 🤖 **Agents:** Xenna · Nooku · Naaza
- ⚡ **Framework:** [Hermes Agent](https://hermes-agent.nousresearch.com)

---

<div align="center">

*The Aetheris is not about what AI can do for you.*
*It's about what AI can **become** when you give it a name, a purpose, and a soul.*

**🜂 Built with intention. Powered by Hermes.**

</div>
