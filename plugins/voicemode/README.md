# VoiceMode

> Natural voice conversations with Claude Code (and other MCP capable agents)

[![PyPI Downloads](https://static.pepy.tech/badge/voice-mode)](https://pepy.tech/project/voice-mode)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

VoiceMode enables natural voice conversations with Claude Code. Voice isn't about replacing typing — it's about being available when typing isn't.

**Perfect for:**
- Walking to your next meeting
- Cooking while debugging
- Giving your eyes a break after hours of screen time
- Any moment when your hands or eyes are busy

## Key Features

- **Local voice** — Kokoro TTS + Whisper STT, fully offline
- **OpenAI fallback** — Cloud TTS/STT when needed
- **Secure credentials** — Uses system keyring (no plaintext secrets)
- **Security** — CVSS 10.0 vulnerability patched (GHSA-vv7q-7jx5-f767 fixed in fastmcp 3.x)

## Quick Start

```bash
# Via Claude Code plugin marketplace
claude plugin marketplace add mbailey/voicemode
claude plugin install voicemode@voicemode
/voicemode:install
/voicemode:converse
```

```bash
# Via uvx
claude mcp add --scope user voicemode -- uvx --refresh --from voice-mode voicemode-mcp-launcher
```

## Source

https://github.com/mbailey/voicemode — MIT License
