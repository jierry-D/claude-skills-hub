# dbhub — Universal Database MCP Server

- **Source**: https://github.com/bytebase/dbhub
- **Stars**: 3,057 ⭐
- **Category**: Database / SQL / MCP
- **Added**: 2026-06-30
- **License**: MIT
- **Security**: PASS — MIT license; dependencies: @modelcontextprotocol/sdk, express, ssh2, zod, pg, mysql2, mssql (all well-known); no hardcoded credentials; no unknown outbound calls; by Bytebase (established DB tooling company)
- **Score**: 94/100
- **Why selected**: Zero-dependency, token-efficient MCP server covering Postgres, MySQL, SQL Server, MariaDB, and SQLite in a single binary; fills the Database/SQL category gap identified in the weekly strategy review.

## Install

```bash
# Claude Code / any MCP client
npx dbhub --transport stdio postgres://user:pass@localhost/dbname
```

Add to `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "dbhub": {
      "command": "npx",
      "args": ["dbhub", "--transport", "stdio", "YOUR_DATABASE_URL"]
    }
  }
}
```

## What It Does

- Natural-language queries against 5+ database engines
- Schema exploration, table listing, query execution
- Token-efficient design — returns only the data AI needs
- SSH tunnel support for remote databases
- Optional read-only mode for safety
