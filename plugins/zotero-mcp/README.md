# Zotero MCP

> Model Context Protocol Integration for Zotero — AI-powered reference management

[![zotero target version](https://img.shields.io/badge/Zotero-7-green?style=flat-square&logo=zotero&logoColor=CC2936)](https://www.zotero.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

Zotero MCP is an open-source project enabling AI assistants (Claude, Gemini CLI, etc.) to interact directly with your local Zotero library via MCP.

## Architecture

```
AI Client ↔ Streamable HTTP ↔ Zotero Plugin (with integrated MCP server)
```

Local-only — no cloud dependencies, no data leaves your machine.

## Capabilities

- **Smart Search** — Multi-dimensional search (title/creator/year/tags/fulltext/semantic) with boolean operators and relevance scoring
- **Content Extraction** — PDF full-text, notes, abstracts, webpage snapshots with fine-grained mode control
- **Annotation Analysis** — Search and analyze PDF highlights and annotations by color, tags, and keywords
- **Collection Browsing** — Browse and search collection hierarchies
- **Semantic Search** — AI-powered concept matching via embedding vectors, cross-language support
- **Write Operations** — Create notes, manage tags, update metadata, create items, attach PDFs
- **Full-text Database** — Access and search cached PDF full-text

## Use Cases

- Literature reviews and citation management
- Annotation organization
- Cross-language academic research
- Knowledge base management from your reference library

## Installation

1. Install the Zotero plugin from the [releases page](https://github.com/cookjohn/zotero-mcp/releases)
2. Configure your AI client with the MCP server endpoint

See the [README](https://github.com/cookjohn/zotero-mcp/blob/main/README.md) for detailed setup.

## Source

https://github.com/cookjohn/zotero-mcp — MIT License
