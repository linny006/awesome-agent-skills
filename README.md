<!--
SEO: awesome agent skills
-->

<div align="center">

# Awesome Agent Skills

Curated, auto-updated awesome-list of vetted AI agent skills with quality ratings for Claude, GPT, and open-source agents

[![Stars](https://img.shields.io/github/stars/linny006-tecch/awesome-agent-skills?style=for-the-badge&logo=github)](https://github.com/linny006-tecch/awesome-agent-skills/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006-tecch/awesome-agent-skills?style=for-the-badge)](https://github.com/linny006-tecch/awesome-agent-skills/commits)
[![Items](https://img.shields.io/badge/Tracked_Items-18-brightgreen?style=for-the-badge)](#)
[![Updated](https://img.shields.io/badge/Updates-every_15min-blue?style=for-the-badge)](#)

**⭐ Star this repo to bookmark — fresh data every 15 minutes**

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · [Español](./README_ES.md) · [Português](./README_PT.md)

</div>

---

## 💡 What is this?

A living, auto-updated directory of functional AI agent skill repositories, evaluated by agent type, quality, and maintenance status. Unlike static awesome-lists, this project uses GitHub Actions to crawl, test, and rate skills daily, ensuring practitioners find only working, high-quality capabilities.

This list is **auto-updated every 15 minutes** by a GitHub Actions cron.
Each commit reflects a real change in the upstream data source — new items added,
expired items removed — so you can rely on what you see being current.

---

## 📋 Current Items

> ⏰ Last updated: 2026-10-27 14:30 UTC
>
> Data source: `GitHub Search API`
>
> The table below is rewritten on every cron tick. Star the repo to bookmark.

<!-- TRACKER_TABLE_START -->
| # | Name | ⭐ | Lang | Updated | Description |
|---|------|---|------|---------|-------------|
| 1 | [netopsengineer/axiom](https://github.com/netopsengineer/axiom) | 5 | Python | 2026-10-27 | Axiom is a curated marketplace of shared plugins for Claude Code and Codex. |
| 2 | [zmievsa/skills](https://github.com/zmievsa/skills) | 1 | Shell | 2026-10-27 | Installable agent skills for testing and strict Python typing |
| 3 | [WuDao0123/taste-skill](https://github.com/WuDao0123/taste-skill) | 0 | JavaScript | 2026-10-27 | Turn any website URL or UI screenshot into an aesthetic SKILL.md for Cursor & Claude Code + 30 flagship brand design sys |
| 4 | [superczach/lunar-gatekeeper-sentinel](https://github.com/superczach/lunar-gatekeeper-sentinel) | 0 | HTML | 2026-10-27 | Lunar Gateway 2026: Agent-Native MCP Security & Governance Hub for AI Workloads |
| 5 | [cjumeow/watch-less](https://github.com/cjumeow/watch-less) | 1 | TypeScript | 2026-10-27 | Hover a YouTube thumbnail to get a neutral, evidence-backed summary in Heptabase |
| 6 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 90236 | JavaScript | 2026-10-27 | Turn any idea, plan, or codebase into a beautiful interactive diagram. An agent skill for Claude Code, Codex, and more. |
| 7 | [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) | 137 | Python | 2026-10-27 | 13 Claude Code skills for video production (transcribe / translate / dub / multicam / subtitles / reframe) + WeChat publ |
| 8 | [evrenverse/agent-skills](https://github.com/evrenverse/agent-skills) | 1 | Python | 2026-10-27 | Claude Code and Codex plugin for working with paseo agents: handoff, spawn, takeover, second opinions, run profiling. |
| 9 | [BrickerP/Personal-Skills](https://github.com/BrickerP/Personal-Skills) | 0 | Python | 2026-10-27 | Single-source agent skills (SKILL.md) symlinked into Codex, Claude Code, Cursor, and OpenCode |
| 10 | [mohamoudj6-del/AlterLab-FC-Agent-Playbook](https://github.com/mohamoudj6-del/AlterLab-FC-Agent-Playbook) | 0 | HTML | 2026-10-27 | AlterLab FC 2026 AI Playbook 🚀 Ultimate Skills & Strategy Guide |
| 11 | [PromptPotter/prompt-potter-optimizer](https://github.com/PromptPotter/prompt-potter-optimizer) | 8 | Python | 2026-10-27 | LLM-driven evolution of prompts and pipelines. Evolves the prompt and the pipeline's parameters together against your la |
| 12 | [trevhud/rote](https://github.com/trevhud/rote) | 8 | Python | 2026-10-27 | Compile AI agent skills into cheap, fast, deterministic pipelines that run without an LLM in the loop |
| 13 | [Aniruddh5502/momo](https://github.com/Aniruddh5502/momo) | 0 | Python | 2026-10-27 | A local-first, tool-augmented agentic AI assistant powered by LangGraph and        Ollama. Orchestrate complex tasks and |
| 14 | [reticlehq/reticle](https://github.com/reticlehq/reticle) | 1275 | TypeScript | 2026-10-27 | AI agents can generate code, but still struggle to understand what they build. Reticle brings Jev-style machine-native r |
| 15 | [EdgeKits/i18n](https://github.com/EdgeKits/i18n) | 0 | TypeScript | 2026-10-27 | Edge-native i18n on Cloudflare Workers: @edgekits/i18n-core (translations in Workers KV, a per-namespace edge cache purg |
| 16 | [altertable-ai/skills](https://github.com/altertable-ai/skills) | 7 | Python | 2026-10-27 | Agent Skills for Altertable |
| 17 | [bitranox/btx-skill-jev-judge](https://github.com/bitranox/btx-skill-jev-judge) | 1 | Python | 2026-10-27 | Claude Code plugin and Python CLI: hand a judgment repeated over many items to TypeSafe's Jev, with redaction, rate limi |
| 18 | [scenario-labs/skills](https://github.com/scenario-labs/skills) | 1169 | Python | 2026-10-27 | Get production-ready images, video, audio, and 3D from any AI agent: skills that pick the right model, price before spen |
<!-- TRACKER_TABLE_END -->

---

## 🔍 How it works

Every 15 minutes, a GitHub Action runs `tracker.py`. That script:

1. Fetches the latest state from `GitHub Search API`.
2. Diffs against `data/items.json` (the previous snapshot).
3. Rewrites the table above between the `<!-- TRACKER_TABLE_* -->` markers.
4. Commits `feat: +N added, -M removed (timestamp)` if anything changed.

No external services. No paid APIs. Just a public data source and a free GitHub Action.

---

## 🤝 Contributing

See `CONTRIBUTING.md` — usually you don't need to: the tracker keeps itself current.
If you spot a data-source bug or want to suggest a new column for the table, open
an issue.

---

## 🔗 Related live trackers

If you find this useful, you might also like these other auto-updated
trackers from the same maintainer — same mechanism, different upstream:

- [trending-claude-skills](https://github.com/linny006/trending-claude-skills) — What's shipping in Claude Skills this week (`topic:claude-skills`)
- [mcp-servers-live](https://github.com/linny006/mcp-servers-live) — Live index of newest MCP servers (`topic:mcp-server`)
- [cursor-rules-live](https://github.com/linny006/cursor-rules-live) — Newest Cursor rules and .cursorrules patterns (`topic:cursor-rules`)
- [claude-code-plugin-tracker](https://github.com/linny006/claude-code-plugin-tracker) — Claude Code plugins and hook configs (`topic:claude-code`)
- [llm-agents-radar](https://github.com/linny006/llm-agents-radar) — Newest LLM agent frameworks (`topic:llm-agent`)
- [rag-radar](https://github.com/linny006/rag-radar) — Newest RAG implementations and tools (`topic:rag`)
- [llm-eval-tracker](https://github.com/linny006/llm-eval-tracker) — Newest LLM evaluation tools and benchmarks (`topic:llm-eval`)
- [agent-framework-radar](https://github.com/linny006/agent-framework-radar) — Newest agent frameworks shipping on GitHub (`topic:agent-framework`)
- [vector-db-live](https://github.com/linny006/vector-db-live) — Newest vector DB projects and integrations (`topic:vector-database`)
- [llmops-radar](https://github.com/linny006/llmops-radar) — Newest LLMOps tooling (observability, deployment) (`topic:llmops`)
- [prompt-tools-live](https://github.com/linny006/prompt-tools-live) — Newest prompt-engineering tools and prompt repos (`topic:prompt-engineering`)
- [agent-eval-harness](https://github.com/linny006/agent-eval-harness) — Live benchmark of AI coding agents (`topic:llm-eval`)
- [skills-tracker](https://github.com/linny006/skills-tracker) — Tracking new GitHub 'skills' repos (`topic:agent-skills`)

---

## 📜 License

MIT — see `LICENSE`.

## More from linny006


- [**Awesome Agent Skills**](https://github.com/linny006/awesome-agent-skills) — Curated, auto-updated awesome-list of vetted AI agent skills with quality ratings for Claude, GPT, and open-source agents (⭐ 0)

- [**Agent Skills Daily Tracker**](https://github.com/linny006/skills-tracker) — Real-time tracking of every new GitHub 'skills' repo to capture the AI agent skill ecosystem trend (⭐ 0)

- [**Agent Eval Harness**](https://github.com/linny006/agent-eval-harness) — Live, open-source benchmark for comparing AI coding agents on real GitHub issues (⭐ 0)

- [**Prompt Tools Live**](https://github.com/linny006/prompt-tools-live) — Live-updating tracker of prompt engineering tools, libraries, and techniques — refreshed every 15 minutes (⭐ 0)

- [**LLMOps Radar**](https://github.com/linny006/llmops-radar) — Live index of the newest LLMOps tooling — track what's shipping in LLM observability and deployment (⭐ 0)
