# serena

> The IDE for Your Coding Agent

Serena provides essential **semantic code retrieval, editing, refactoring and debugging tools** akin to an IDE's capabilities, operating at the symbol level and exploiting relational structure. It integrates with any client/LLM via the Model Context Protocol (MCP).

Serena's **agent-first tool design** involves robust high-level abstractions, distinguishing it from approaches that rely on low-level concepts like line numbers or primitive search patterns.

## What agents say

**Opus 4.6 (high) in Claude Code:**
> "Serena's IDE-backed semantic tools are the single most impactful addition to my toolkit — cross-file renames, moves, and reference lookups that would cost me 8–12 careful, error-prone steps collapse into one atomic call."

**GPT 5.4 (high) in Codex CLI:**
> "It gives me the missing IDE-level understanding of symbols, references, and refactorings, turning fragile text surgery into calmer, faster, more confident code changes."

## Key Features

- Symbol-aware navigation and cross-file refactoring
- Semantic search (find-by-symbol, find-references, rename-symbol)
- Language server protocol (LSP) integration
- Multi-language support (Python, Java, TypeScript, Rust, Go, etc.)
- Zero-hallucination edits via structural awareness
- Works with Claude Code, Cursor, Copilot CLI, Codex CLI

## Quick Start

```bash
uvx --from serena-agent serena --project /path/to/project
```

See the [Quick Start Guide](https://github.com/oraios/serena#quick-start) for full setup instructions.

## Source

https://github.com/oraios/serena — MIT License
