# cursor-talk-to-figma-mcp — Figma MCP Integration for AI Agents

- **Source**: https://github.com/grab/cursor-talk-to-figma-mcp
- **Stars**: 6,865 ⭐
- **Category**: Design Tool / Figma MCP
- **Added**: 2026-06-30
- **License**: MIT
- **Security**: PASS — MIT license; minimal dependencies (@modelcontextprotocol/sdk, uuid, ws, zod); outbound calls only to Figma API (documented, user-authenticated); no hardcoded credentials; maintained by Grab (major tech company); no telemetry
- **Score**: 89/100
- **Why selected**: Gives AI agents the ability to read Figma designs and modify them programmatically — a distinct, design-workflow angle complementing the existing Open Design plugin, from a trusted enterprise maintainer.

## Install

```bash
bun install
bun run build

# Add to claude_desktop_config.json
```

```json
{
  "mcpServers": {
    "figma": {
      "command": "node",
      "args": ["/path/to/cursor-talk-to-figma-mcp/dist/socket.js"]
    }
  }
}
```

## What It Does

- Read Figma file structure, components, frames, and layers
- Modify Figma designs programmatically from AI agent instructions
- WebSocket bridge between AI agent and Figma desktop plugin
- Supports Claude Code, Cursor, Codex, and any MCP-compatible client
- Maintained by Grab engineering team
