# code-review-graph — Local Code Intelligence Graph for MCP & CLI

- **Source**: https://github.com/tirth8205/code-review-graph
- **Stars**: 18,996 ⭐
- **Category**: Code Intelligence / Code Review / MCP
- **Added**: 2026-06-30
- **License**: MIT
- **Security**: PASS — MIT license; dependencies: mcp, fastmcp (pins CVE-2025-62800/62801/66416 fixes), tree-sitter, networkx, watchdog (all established libraries); zero telemetry explicitly stated; offline-first with local SQLite storage; network calls only if user opts in for embeddings; no hardcoded credentials
- **Score**: 92/100
- **Why selected**: Builds a persistent codebase graph via Tree-sitter, reducing code-review token usage by a median of ~82x. Zero-telemetry local design and auto-detection of Claude/Cursor/Windsurf/Copilot make it a practical daily driver for large repos.

## Install

```bash
pip install code-review-graph
code-review-graph install   # auto-detects AI platforms
code-review-graph build     # indexes your repo into local SQLite
```

## What It Does

- Tree-sitter AST analysis of entire codebase → local SQLite graph
- Identifies "blast radius" of any code change
- Feeds AI assistants only relevant context (~82x fewer tokens)
- Auto-detects and configures Claude Code, Cursor, Windsurf, GitHub Copilot
- Optional vector embeddings (Google Gemini, MiniMax, OpenAI) — off by default
- Zero telemetry; all data stays on local machine
