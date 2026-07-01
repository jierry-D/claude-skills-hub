# Unity-MCP

> AI Skills, MCP Tools, and CLI for Unity Engine — Full AI develop and test loop

[![MCP](https://badge.mcpx.dev 'MCP Server')](https://modelcontextprotocol.io/introduction)
[![License](https://img.shields.io/github/license/IvanMurzak/Unity-MCP)](https://github.com/IvanMurzak/Unity-MCP/blob/main/LICENSE)

`Unity MCP` is an AI-powered game development assistant **for Editor & Runtime**. Connect Claude, Cursor, & Windsurf to Unity via MCP. Automate workflows, generate code, and **enable AI within your games**.

Unlike other tools, this plugin works **inside your compiled game**, allowing for real-time AI debugging and player-AI interaction.

## Key Features

- **AI agents** — Use the best agents from Anthropic, OpenAI, Microsoft, or any other provider with no vendor lock-in
- **Tools** — Wide range of default MCP Tools for operating in Unity Editor
- **Skills** — Generate skills for AI based on OS, Unity version, and project plugins
- **Runtime (in-game)** — Use LLMs directly inside your compiled game for dynamic NPC behavior or debugging
- **Extensible** — Create custom Tools with a single C# attribute decorator
- **Flexible deployment** — Works locally (stdio) and remotely (http)

## Installation

**Recommended: Download the installer package**
```
https://github.com/IvanMurzak/Unity-MCP/releases/latest/download/AI-Game-Dev-Installer.unitypackage
```

**Or via CLI:**
```bash
openupm add com.ivanmurzak.unity.mcp
```

**Or via Docker:**
```bash
docker pull aigamedeveloper/mcp-server:latest
```

Languages: [中文](docs/README.zh-CN.md) | [日本語](docs/README.ja.md) | [Español](docs/README.es.md)

## Source

https://github.com/IvanMurzak/Unity-MCP — MIT License
