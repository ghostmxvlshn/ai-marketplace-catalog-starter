# Company Agent Tools Marketplace (Starter)

Internal GitHub starter for a Claude Code plugin marketplace with team-separated ownership.

## Goals
- Central discovery (`marketplace.json`)
- Decentralized ownership (one plugin repo per team)
- Safe governance (CODEOWNERS + branch protections + versioning)

## Suggested team plugin repos
- `company/ai-plugin-devops`
- `company/ai-plugin-backend-core`
- `company/ai-plugin-frontend`
- `company/ai-plugin-shared-standards`

## Install (example)
```bash
/plugin marketplace add https://github.com/<org>/ai-marketplace-catalog
/plugin install devops-tools@company-agent-tools
```

See `docs/REPO-PLAN.md` for detailed ownership model.
