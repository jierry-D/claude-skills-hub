# terraform-skill — Terraform & OpenTofu Skill for AI Agents

- **Source**: https://github.com/antonbabenko/terraform-skill
- **Stars**: 2,086 ⭐
- **Category**: DevOps / Infrastructure-as-Code
- **Added**: 2026-06-30
- **License**: Apache 2.0
- **Security**: PASS — Apache 2.0 license; pure skill/markdown (no code execution); no telemetry; optional HashiCorp terraform-mcp-server integration (user-controlled); no unknown outbound calls; authored by Anton Babenko (prominent Terraform OSS maintainer)
- **Score**: 91/100
- **Why selected**: Fills the DevOps/IaC gap identified in the weekly strategy review; authored by a highly respected Terraform community maintainer, covering testing, modules, CI/CD, multi-cloud patterns for Terraform and OpenTofu.

## Install

```bash
# Claude Code
/plugin marketplace add antonbabenko/agent-plugins
# then: install terraform-skill

# Generic install
npx skills add https://github.com/antonbabenko/terraform-skill

# Manual — clone to skills dir
git clone --depth=1 https://github.com/antonbabenko/terraform-skill ~/.claude/skills/terraform-skill
```

## What It Does

- Best-practice guidance for Terraform & OpenTofu modules
- CI/CD pipeline integration patterns (GitHub Actions, GitLab CI)
- Testing frameworks: Terratest, OpenTofu testing
- State management and workspace patterns
- Security scanning integration (Trivy, Checkov, TFLint)
- Multi-cloud (AWS, Azure, GCP) module patterns
