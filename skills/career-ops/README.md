# Career-Ops — AI-Powered Job Search System

> Source: https://github.com/santifer/career-ops — 56,179 ⭐

## Overview

An open-source AI-powered job search system that automates evaluation, application tracking, and resume customization. Built by Santiago (Head of Applied AI).

## Core Capabilities

- **Auto-Pipeline**: Paste a URL to receive full evaluation, PDF generation, and tracker entry
- **6-Block Evaluation**: Role summary, CV compatibility, level strategy, compensation research, personalization, interview prep
- **Interview Story Bank**: Accumulates behavioral narratives across evaluations
- **Cover Letter Generator**: AI-drafted letters with keyword mirroring and PDF output
- **Portal Scanner**: Pre-configured access to 45+ company career portals (Anthropic, OpenAI, ElevenLabs, Ashby, Greenhouse, Lever, Wellfound, and more)
- **Dashboard TUI**: Terminal interface for browsing and filtering applications (Go/Bubble Tea)

## Technical Foundation

Built with Claude Code, Node.js, Playwright for automation, and Go (Bubble Tea) for the dashboard. Works across Claude Code, OpenCode, Antigravity CLI, and Grok Build CLI.

## Important Context

Human oversight enforced — AI evaluates and recommends, but users retain final decision authority. Applications are **never** submitted automatically.

## Installation

```bash
npx @santifer/career-ops init
# then use:
/career-ops <job URL or description>
```

MIT licensed. JavaScript (78.6%) + Go (15%).
