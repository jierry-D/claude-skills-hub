# Planning with Files — Persistent Context for AI Agents

> Source: https://github.com/OthmanAdi/planning-with-files — 24,028 ⭐

## Core Innovation

Uses the filesystem as durable working memory. Rather than storing plans solely in the context window (volatile RAM), it maintains three markdown files:

- `task_plan.md` — phases and progress tracking
- `findings.md` — research and discoveries  
- `progress.md` — session logs and test results

Plans automatically recover after context loss through session detection that extracts conversation following the last file update.

## Key Features

- **96.7% pass rate** (v2.21.0 on Claude Sonnet 4.6)
- **A/B tested:** 3/3 blind comparison wins
- **Security audited** and SkillCheck validated
- **SHA-256 attestation** for plan tamper-detection (`/plan-attest`)
- **17+ IDE platforms**: Claude Code, Cursor, GitHub Copilot, Codex, Gemini CLI, and more
- **5 languages**: Arabic, German, Spanish, Simplified/Traditional Chinese
- **Autonomous Mode (v3.0+)**: Gated completion prevents incomplete plans from trapping sessions

## Best For

Multi-step tasks, research, building projects, and any work spanning 3+ steps or numerous tool calls. Skip for simple questions or single-file edits.

## Installation

```bash
npx skills add OthmanAdi/planning-with-files --skill planning-with-files -g
```

MIT licensed. 184 tests. 71 releases.
