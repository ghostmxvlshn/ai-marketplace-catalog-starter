# Repository Separation Plan

## Topology
- `ai-marketplace-catalog` (central index)
- `ai-plugin-devops`
- `ai-plugin-backend-core`
- `ai-plugin-frontend`
- `ai-plugin-shared-standards`

## Ownership
- Catalog owned by Platform/AI Enablement.
- Team plugin repos owned by respective teams.
- Platform team has read + emergency admin.

## Governance (minimum)
- Branch protection: PR required, no force-push, status checks required.
- CODEOWNERS required for plugin files.
- Semantic versioning in each plugin repo.
- CHANGELOG required for every release.

## Risk model
Each skill/agent must declare risk level:
- `read-only`
- `propose-changes`
- `execute-changes` (requires explicit human approval)

## Rollout
1. Pilot with DevOps + Backend + Frontend leads.
2. Measure adoption and time saved.
3. Expand plugins and enforce quality gates.
