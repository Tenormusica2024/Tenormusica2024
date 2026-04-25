## Hi there

I’m an AI Engineer focused on agent operations, knowledge operations, and automation reliability.

I build automation systems and LLM/agent workflows that are not only functional, but also operable, monitorable, and maintainable in real-world environments. My specialty is tying tools, workflows, and repositories together into automation that doesn’t break.

---

### Start here: public repos that show how I work

Most of my larger operating systems are private or partially private.  
If you want the fastest public entry points, start with these:

- **Review / fix workflows**
  - [review-fix-pipeline](https://github.com/Tenormusica2024/review-fix-pipeline) — intent-first review and automated fix loops with independent reviewer contexts
  - [claude-review-pdca](https://github.com/Tenormusica2024/claude-review-pdca) — closed-loop reuse of past review findings during implementation
  - [claude-code-hooks](https://github.com/Tenormusica2024/claude-code-hooks) — guardrails that block user-delegation and premature completion
- **Knowledge / documentation operations**
  - [x-bookmark-knowledge-pack](https://github.com/Tenormusica2024/x-bookmark-knowledge-pack) — local-first X bookmark pack generator for humans and AI agents
  - [doc-freshness-analyzer](https://github.com/Tenormusica2024/doc-freshness-analyzer) — verify README/docs claims against actual code reality
- **Data pipeline / dashboard artifact**
  - [huggingface-daily-insights-api](https://github.com/Tenormusica2024/huggingface-daily-insights-api) — daily snapshots, dashboard, CSV releases, and API for open AI ecosystem tracking

If you only open **one** repo first, start with [review-fix-pipeline](https://github.com/Tenormusica2024/review-fix-pipeline) for agent workflow design or [x-bookmark-knowledge-pack](https://github.com/Tenormusica2024/x-bookmark-knowledge-pack) for knowledge-pack style local-first tooling.

---

### Featured: curiosity-wiki Operations Flow

End-to-end view of the operations pipeline for a personal LLM Wiki.
Visualizes the data flow from a Task Scheduler-triggered orchestrator, through the intake / governance / graphify flows, down to the operations cockpit.

[![curiosity-wiki Operations Flow](./assets/curiosity-wiki-fullmap.png)](https://curiosity-wiki-ops.vercel.app)

**Live demo:** https://curiosity-wiki-ops.vercel.app

- 8-agent sensitivity-optimized pipeline (Phase 5)
- Concept normalization + alias resolution via a canonical layer (Phase 6)
- Automated intake 4x/day + weekly governance + daily meta supervision
- Multi-source search chain across Grok 4 / Perplexity / xAI API
- Multi-model orchestration with GLM-5 × Claude Code × Codex

The main repository is private. Only the visualization HTML is carved out into a standalone deploy repository and published via Vercel.

---

### Representative Projects

- **curiosity-wiki** — track-aware research and knowledge operations system for AI-agent-friendly workflows  
  Demo: https://curiosity-wiki-ops.vercel.app
- **openclaw-claude-bridge** — bridge-oriented orchestration for multi-agent execution and operational routing  
  Repo: https://github.com/Tenormusica2024/openclaw-claude-bridge
- **vault-d** — metadata normalization and knowledge structure design for durable AI workflows  
  Repo: https://github.com/Tenormusica2024/vault-d

### Selected Artifacts

- **curiosity-wiki Operations Flow (live demo)**  
  https://curiosity-wiki-ops.vercel.app
- **openclaw-claude-bridge**  
  https://github.com/Tenormusica2024/openclaw-claude-bridge
- **vault-d**  
  https://github.com/Tenormusica2024/vault-d
- **Portfolio** — personal portfolio site showcasing selected projects, AI workflow work, and implementation context  
  https://github.com/Tenormusica2024/portfolio

---

### Stack

- **Languages:** Python, TypeScript, PowerShell, Bash
- **AI / Agents:** Claude Code (Opus / Sonnet), Codex (GPT-5.4), GLM-5, Grok 4
- **Automation:** Task Scheduler, GitHub Actions, Vercel, Cloud Run
- **Knowledge Ops:** Obsidian Vault, frontmatter metadata, semantic graph (graphify)
- **Orchestration:** Claude in Chrome (CiC), Playwright CLI, dev-browser, MCP servers

---

### Focus

- Agent operations and AI workflow reliability
- Knowledge operations and agent-friendly structure design
- Cost-aware model routing and role separation
- Safe automation that reduces manual routing and repetitive judgment
- Guardrails, monitoring, and handover for real-world operation
