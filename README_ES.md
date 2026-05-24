# awesome-agent-skills

> Lista awesome curada y auto-actualizada de habilidades de agentes IA con puntuaciones de calidad para Claude, GPT y agentes de código abierto

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · [한국어](./README_KO.md) · **Español** · [Português](./README_PT.md)

[![Stars](https://img.shields.io/github/stars/linny006/awesome-agent-skills?style=for-the-badge&logo=github)](https://github.com/linny006/awesome-agent-skills/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/awesome-agent-skills?style=for-the-badge)](https://github.com/linny006/awesome-agent-skills/commits)

---

Un directorio vivo y auto-actualizado de repositorios de habilidades de agentes IA funcionales, evaluados por tipo de agente, calidad y estado de mantenimiento. A diferencia de las awesome-lists estáticas, este proyecto usa GitHub Actions para rastrear, probar y puntuar habilidades a diario, asegurando que solo encuentres capacidades que funcionan y son de alta calidad.

Esta lista se **actualiza automáticamente cada 15 minutos** mediante un cron de GitHub Actions. Cada commit refleja un cambio real en la fuente de datos upstream — nuevos elementos añadidos, elementos expirados eliminados — así que puedes confiar en que lo que ves está al día.

---

Cada 15 minutos, un GitHub Action ejecuta `tracker.py`. Ese script:

1. Obtiene el estado más reciente desde la `GitHub Search API`.
2. Compara con `data/items.json` (el snapshot anterior).
3. Reescribe la tabla de arriba entre los marcadores `<!-- TRACKER_TABLE_* -->`.
4. Hace commit de `feat: +N added, -M removed (timestamp)` si hubo cambios.

Sin servicios externos. Sin APIs de pago. Solo una fuente de datos pública y un GitHub Action gratuito.

---

## 📋 Live data

Los datos en tiempo real están en el README en inglés

---

## 🔗 Related live trackers

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
