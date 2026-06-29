# Claude Code Plugins — Official Directory

> Source: https://github.com/anthropics/claude-plugins-official

Official, Anthropic-managed directory of high-quality Claude Code Plugins. 31,264 ⭐

## Structure

- **Internal plugins**: Developed by Anthropic
- **External plugins**: Third-party, reviewed by Anthropic before acceptance

## Plugin Format

Each plugin contains:
- `plugin.json` — metadata and capabilities
- Optional MCP server configuration
- Directories for commands, agents, and skills

## Installation

```bash
/plugin install {plugin-name}@claude-plugins-official
```

## Contributing

External plugins must pass quality and security review. Submit via the official contribution form linked in the repo.

## Skill-Bundle Feature

Plugins can bundle multiple skills from source repositories — useful for curating subsets of large skill libraries without individual manifests.

> **Note**: Anthropic does not control what MCP servers or third-party software plugins include. Always review a plugin before installing.

**License:** Per individual plugin (see each plugin's LICENSE file)
