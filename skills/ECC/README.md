# ECC: Agent Harness Operating System

> Source: https://github.com/affaan-m/ECC — 222,624 ⭐

## Overview

ECC is a comprehensive plugin system for Claude Code and compatible AI development tools. It provides production-ready agents, skills, hooks, rules, and MCP configurations built from real-world engineering workflows.

## Key Components

**Agents (67 total):** Specialized subagents handle delegated tasks including code review, architecture design, TDD guidance, security analysis, and language-specific development (Go, Python, TypeScript, Java, Rust, C++, etc.).

**Skills (271 total):** Workflow definitions covering coding standards, backend/frontend patterns, continuous learning, testing frameworks, and domain expertise across multiple languages and frameworks.

**Commands (92 total):** Slash-entry points for implementation planning, code review, build fixes, refactoring, and model routing.

**Hooks:** Event-triggered automations including session persistence, strategic compaction, secret detection, and development server guards.

**Rules (34 total):** Always-follow guidelines organized by language, covering coding style, security, testing (80%+ coverage requirement), performance, and git workflows.

## Installation

```
/plugin marketplace add https://github.com/affaan-m/ECC
/plugin install ecc@ecc
```

## Security

Built-in AgentShield audits configurations for injection, secrets, and permission misconfigurations. MIT licensed.
