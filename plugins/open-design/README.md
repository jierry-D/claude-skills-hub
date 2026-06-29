# Open Design — The open-source Claude Design alternative

> Source: https://github.com/nexu-io/open-design

Local-first, open-source Claude Design alternative. Native desktop app (macOS/Windows). 72,415 ⭐

## What it provides

- **100+ skills** for prototypes, dashboards, decks, images, HyperFrames (motion graphics)
- **150 brand-grade `DESIGN.md` systems** — 9-section brand contracts (color, typography, spacing, components, motion, voice)
- **261 ready-to-use plugins** organized by scenario
- **MCP server** — `od mcp install <agent>` wires into any agent
- **Export**: HTML, PDF, PPTX, MP4, ZIP, Markdown

## Agent Compatibility

Claude Code · OpenClaw · Codex · Cursor · OpenCode · Qwen · Copilot · Hermes · Kimi · Antigravity and 22 local CLIs, or any OpenAI-compatible endpoint via BYOK.

## Architecture

- Local-first: all processing on your device
- BYOK with SSRF protection (blocks internal IPs)
- Sandboxed iframe preview for all artifacts
- Optional AMR model router (GPT/Claude/Gemini/DeepSeek, billed by real token usage)

## Quick Start

```bash
# macOS/Windows: download from
# https://github.com/nexu-io/open-design/releases

# Or Docker:
docker run -p 3000:3000 nexuio/open-design
```

**License:** Apache-2.0
