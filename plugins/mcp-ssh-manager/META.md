# mcp-ssh-manager — SSH Management MCP Server (37 Tools)

- **Source**: https://github.com/bvisible/mcp-ssh-manager
- **Stars**: 332 ⭐
- **Category**: DevOps / SSH Management / Remote Operations
- **Added**: 2026-06-30
- **License**: MIT
- **Security**: PASS — MIT license; dependencies: @modelcontextprotocol/sdk, ssh2, zod, dotenv, uuid (all legitimate, well-maintained); SSH connections are user-configured via .ssh/config — no hardcoded hosts or credentials; no unknown outbound calls; environment-variable-based credential management
- **Score**: 77/100
- **Why selected**: Fills the DevOps SSH gap with 37 MCP tools for remote server management, backup operations, database ops, and health monitoring — practical for teams using Claude Code for server automation and infrastructure management.

## Install

```bash
npm install -g mcp-ssh-manager

# Add to claude_desktop_config.json
```

```json
{
  "mcpServers": {
    "ssh-manager": {
      "command": "mcp-ssh-manager",
      "env": {
        "SSH_CONFIG_PATH": "~/.ssh/config"
      }
    }
  }
}
```

## What It Does

- 37 tools for remote SSH server management
- Backup automation and restore operations
- Database operations via SSH tunnel
- Health monitoring and log inspection
- ERPNext/Frappe server management (specialized tooling)
- Compatible: Claude Code, Codex, and any MCP client
