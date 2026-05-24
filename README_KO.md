# awesome-agent-skills

> Claude, GPT, 오픈소스 에이전트를 위한 품질 평가 포함, 엄선된 자동 업데이트 AI 에이전트 스킬 awesome-list

[English](./README.md) · [中文](./README_CN.md) · [日本語](./README_JA.md) · **한국어** · [Español](./README_ES.md) · [Português](./README_PT.md)

[![Stars](https://img.shields.io/github/stars/linny006/awesome-agent-skills?style=for-the-badge&logo=github)](https://github.com/linny006/awesome-agent-skills/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/linny006/awesome-agent-skills?style=for-the-badge)](https://github.com/linny006/awesome-agent-skills/commits)

---

에이전트 유형, 품질, 유지보수 상태로 평가된 AI 에이전트 스킬 저장소의 살아있는 디렉토리입니다. 정적인 awesome-list와 달리, 이 프로젝트는 GitHub Actions를 사용해 매일 스킬을 크롤링·테스트·평가하여 실제로 동작하는 고품질 기능만 찾을 수 있도록 합니다.

이 목록은 GitHub Actions cron에 의해 **15분마다 자동 업데이트**됩니다. 각 커밋은 업스트림 데이터 소스의 실제 변경 사항(새 항목 추가, 만료 항목 제거)을 반영하므로, 표시된 내용이 항상 최신임을 신뢰할 수 있습니다.

---

15분마다 GitHub Action이 `tracker.py`를 실행합니다. 이 스크립트는 다음을 수행합니다:

1. `GitHub Search API`에서 최신 상태를 가져옵니다.
2. `data/items.json`(이전 스냅샷)과 diff를 비교합니다.
3. `<!-- TRACKER_TABLE_* -->` 마커 사이의 테이블을 다시 씁니다.
4. 변경 사항이 있으면 `feat: +N added, -M removed (timestamp)`를 커밋합니다.

외부 서비스 없음. 유료 API 없음. 공개 데이터 소스와 무료 GitHub Action만으로 동작합니다.

---

## 📋 Live data

실시간 데이터는 영문 README를 참고하세요

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
