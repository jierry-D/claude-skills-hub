# Agent Skills: Production-Grade Engineering Workflows

> Source: https://github.com/addyosmani/agent-skills — 67,274 ⭐

## Overview

A structured collection of 24 specialized workflows designed to guide AI coding agents through professional software development practices. The package encodes the approaches that senior engineers follow across the entire development lifecycle.

## Six Development Phases

- **Define** (`/spec`): Clarify requirements before coding
- **Plan** (`/plan`): Decompose work into verifiable tasks
- **Build** (`/build`): Implement incrementally with test coverage
- **Verify** (`/test`): Prove functionality through automated testing
- **Review** (`/review`): Apply quality gates before merging
- **Ship** (`/ship`): Deploy with confidence and monitoring

## Key Features

- 24 integrated skills + 4 specialist personas (code reviewer, test engineer, security auditor, web performance auditor)
- Anti-rationalization tables addressing common excuses to skip steps
- Framework-aware activation (designing APIs triggers interface-design practices automatically)
- Draws from Google engineering culture: Hyrum's Law, Beyonce Rule, Chesterton's Fence, trunk-based development

## Philosophical Foundation

Code is treated as a liability requiring deprecation and migration planning. The `/build auto` variant removes manual stepping between tasks while preserving TDD practices.

## Installation

Skills are plain Markdown, compatible with Claude Code, Cursor, Antigravity CLI, Gemini CLI, Windsurf, GitHub Copilot, and more. MIT licensed.
