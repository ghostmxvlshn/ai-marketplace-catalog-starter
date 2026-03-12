# mxstart Agent Marketplace

Production-ready starter for the **mxstart** internal Claude Code plugin marketplace.

## Purpose
Centralize team-specific agents and skills (DevOps, Backend, Frontend, Shared Standards) with clear ownership, governance, and versioning.

## Repository layout
- `.claude-plugin/marketplace.json` — marketplace catalog
- `plugins/devops-tools` — DevOps team plugin
- `plugins/backend-core-tools` — Backend team plugin
- `docs/REPO-PLAN.md` — ownership and governance model

## Installation (example)
```bash
/plugin marketplace add https://github.com/mxstart/ai-marketplace
/plugin install devops-tools@mxstart-agent-tools
```

## Governance
- PR reviews required
- CODEOWNERS required
- Semantic versioning for plugin manifests
- Human approval required for any production-impacting actions
