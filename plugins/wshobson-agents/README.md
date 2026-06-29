# Agents Plugin Marketplace

> Source: https://github.com/wshobson/agents

Production-ready agentic plugin marketplace for Claude Code, Codex CLI, Cursor, OpenCode, Gemini CLI, and GitHub Copilot. 37,296 ⭐

## Contents

| Type | Count |
|------|-------|
| Plugins | 88 |
| Agents | 194 |
| Skills | 158 |
| Commands | 106 |
| Orchestrators | 16 |

## Architecture

"One source-of-truth (`plugins/`), five harnesses" — each platform receives idiomatic, harness-native artifacts, not lowest-common-denominator translations.

## Quality Assurance

Three-layer `plugin-eval` framework:
1. Static structural analysis (<2 seconds)
2. LLM-based semantic evaluation (~30 seconds)
3. Monte Carlo statistical reliability testing (2–5 minutes)

## Installation

```bash
# Claude Code:
/plugin marketplace add wshobson/agents
/plugin install python-development

# Cursor/Codex/others: clone and generate harness artifacts via Makefile
```

**License:** MIT
