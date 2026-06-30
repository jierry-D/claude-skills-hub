# headroom — Token Compression Proxy for AI Agents

- **Source**: https://github.com/headroomlabs-ai/headroom
- **Stars**: 53,884 ⭐
- **Category**: Token Optimization / MCP Proxy / Context Engineering
- **Added**: 2026-06-30
- **License**: Apache 2.0
- **Security**: PASS — Apache 2.0 license; dependencies: tiktoken, pydantic, litellm, click (all established libraries); explicitly pins transitive CVE fixes (pygments, gitpython, langsmith); outbound calls only to user-configured LLM APIs; no telemetry; transparent data flow
- **Score**: 95/100
- **Why selected**: Achieves 60-95% token reduction by compressing tool outputs, logs, and RAG chunks before they reach the LLM. Available as a Python library, drop-in proxy, and MCP server — broadens the token optimization category beyond style-level solutions like Caveman.

## Install

```bash
pip install headroom

# As MCP server (add to Claude Code MCP config)
headroom serve

# As proxy (transparent mode)
headroom proxy --port 8080 --target https://api.anthropic.com
```

## What It Does

- Compresses tool outputs, file content, and RAG chunks (60-95% fewer tokens)
- Works as a Python library, HTTP proxy, or MCP server
- Supports 20+ optional integrations: LangChain, Agno, Strands, voice, vector DBs
- OpenTelemetry tracing support
- Configurable via TOML, works with any MCP-compatible AI client
