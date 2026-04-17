## Hi there

AI エージェント運用とナレッジオペレーションを中心に、実務で動く自動化システムを作っています。
ツール・ワークフロー・リポジトリを束ねて「壊れない自動化」を組み立てるのが専門。

---

### Featured: curiosity-wiki Operations Flow

個人用 LLM Wiki の運用パイプライン全体像。
Task Scheduler が起動するオーケストレーターから、intake / governance / graphify の各フローを経て operations cockpit に集約されるまでのデータフローを可視化。

[![curiosity-wiki Operations Flow](./assets/curiosity-wiki-fullmap.png)](https://curiosity-wiki-ops.vercel.app)

**Live demo:** https://curiosity-wiki-ops.vercel.app

- 8 エージェント構成の感度最適化パイプライン (Phase 5)
- Canonical レイヤーによる概念正規化 + エイリアス解決 (Phase 6)
- 1 日 4 回の自動 intake + 週次 governance + daily meta 監督
- Grok 4 / Perplexity / xAI API のマルチソース検索チェーン
- GLM-5 × Claude Code × Codex のマルチモデル・オーケストレーション

本体リポジトリは非公開。可視化 HTML 1 枚を独立デプロイリポジトリ経由で Vercel 公開しています。

---

### Stack

- **Languages:** Python, TypeScript, PowerShell, Bash
- **AI / Agents:** Claude Code (Opus / Sonnet), Codex (GPT-5.4), GLM-5, Grok 4
- **Automation:** Task Scheduler, GitHub Actions, Vercel, Cloud Run
- **Knowledge Ops:** Obsidian Vault, frontmatter metadata, semantic graph (graphify)
- **Orchestration:** Claude in Chrome (CiC), Playwright CLI, dev-browser, MCP servers

---

### Focus

- AI エージェントが読み書きしやすいナレッジ構造の設計
- モデル役割分担によるコスト最適化（安いモデルに安い仕事、高いモデルに高価値タスク）
- 手動ルーティング・反復判断を安全な自動化で削減
- 動き始めたシステムにガード・監視・自動化を重ねて運用信頼性を高める
