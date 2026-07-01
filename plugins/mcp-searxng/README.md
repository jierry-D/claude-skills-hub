# SearXNG MCP Server

> Private web search for AI assistants — connect any SearXNG instance to Claude, Cursor, and more

[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/ihor-sokoliuk/mcp-searxng/badge)](https://scorecard.dev/viewer/?uri=github.com/ihor-sokoliuk/mcp-searxng)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/13143/badge)](https://www.bestpractices.dev/projects/13143)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

An MCP server integrating the SearXNG API, giving AI assistants web search capabilities without sending queries to centralized services.

## Features

- **Web Search** — General queries, news, articles with pagination
- **Instance Failover** — Multiple SearXNG replicas, automatic failover + parallel fan-out
- **Structured Output** — Formatted text or raw JSON with `response_format`
- **URL Content Reading** — Advanced extraction with pagination and heading extraction
- **Intelligent Caching** — URL content cached with TTL
- **Time Filtering** — Filter results by day/week/month/year
- **Language Selection** — Filter by preferred language
- **Safe Search** — Configurable content filtering
- **Privacy** — All search traffic stays within your SearXNG instance

## Quick Start

```json
{
  "mcpServers": {
    "searxng": {
      "command": "npx",
      "args": ["-y", "mcp-searxng"],
      "env": {
        "SEARXNG_URL": "https://your-searxng-instance.example.com"
      }
    }
  }
}
```

## Source

https://github.com/ihor-sokoliuk/mcp-searxng — MIT License
