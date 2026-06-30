# ARIS — Auto-Research-In-Sleep: Autonomous ML Research Skills

- **Source**: https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep
- **Stars**: 12,790 ⭐
- **Category**: ML Research Automation / Data Science
- **Added**: 2026-06-30
- **License**: MIT
- **Security**: PASS — MIT license; Markdown-only skills (no executable code in skill files); outbound calls only to documented academic APIs (arXiv, CrossRef, Semantic Scholar, DBLP) and user-configured LLM providers; local-only logging in .aris/traces/; no vendor telemetry; API keys loaded from shell env / Keychain only
- **Score**: 88/100
- **Why selected**: Fills the Data Science / ML Engineering category gap; enables fully autonomous multi-stage research pipelines (literature → ideation → experiments → paper → peer review) without framework lock-in, using lightweight Markdown skills compatible with Claude Code, Codex, and OpenClaw.

## Install

```bash
git clone https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep.git
bash Auto-claude-code-research-in-sleep/tools/install_aris.sh ~/your-project
```

## What It Does

- Autonomous literature discovery (arXiv, Semantic Scholar, DBLP, CrossRef)
- Idea generation and experiment design skill chain
- Multi-model cross-review (GPT, Gemini, Claude — user-configured)
- Paper writing and LaTeX / Overleaf sync (optional)
- Local-only audit logs in `.aris/traces/`
- Works with Claude Code, Codex CLI, OpenClaw — no framework required
