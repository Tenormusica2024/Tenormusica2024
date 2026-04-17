## Hi there

I build automation systems that run in real-world operations, centered on AI agent orchestration and knowledge operations.
My specialty is tying tools, workflows, and repositories together into automation that doesn't break.

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

### Stack

- **Languages:** Python, TypeScript, PowerShell, Bash
- **AI / Agents:** Claude Code (Opus / Sonnet), Codex (GPT-5.4), GLM-5, Grok 4
- **Automation:** Task Scheduler, GitHub Actions, Vercel, Cloud Run
- **Knowledge Ops:** Obsidian Vault, frontmatter metadata, semantic graph (graphify)
- **Orchestration:** Claude in Chrome (CiC), Playwright CLI, dev-browser, MCP servers

---

### Focus

- Designing knowledge structures that AI agents can read and write easily
- Cost optimization through model role separation (cheap models for cheap work, premium models for high-value tasks)
- Reducing manual routing and repetitive judgment through safe automation
- Adding guards, monitoring, and automation on top of working systems to raise operational reliability
