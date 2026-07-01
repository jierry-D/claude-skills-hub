# voicemode — Natural Voice Conversations with Claude Code
- **Source**: https://github.com/mbailey/voicemode
- **Stars**: 1,249 ⭐
- **Category**: plugin / voice-audio-interface
- **Added**: 2026-07-01
- **Security**: PASS — MIT license; pyproject.toml explicitly documents CVSS 10.0 fix (fastmcp migrated to 3.x, GHSA-vv7q-7jx5-f767); all external calls use documented APIs (OpenAI TTS/STT, local Kokoro/Whisper); keyring for secure credential storage; no hardcoded API keys; published on PyPI as voice-mode
- **Score**: 90/100
- **Why selected**: The only voice MCP server purpose-built for Claude Code, enabling hands-free development when hands or eyes are busy (cooking, walking, meetings). Supports local voice services (Kokoro TTS, Whisper STT) for fully offline operation, with OpenAI as fallback. A genuinely new interaction modality for the Claude Code ecosystem.
