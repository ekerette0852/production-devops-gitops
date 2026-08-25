# Production DevOps GitOps

GitOps repository for the Production DevOps Platform.

## Deployment Flow

GitHub
→ Jenkins CI
→ GitOps repository
→ Argo CD
→ Kubernetes

## Structure

- `apps/production-app/` - Kubernetes application manifests
- `argocd/` - Argo CD Application definitions

## GitOps Principles

- Git is the source of truth
- Argo CD continuously reconciles Kubernetes state
- Automated synchronization enabled
- Self-healing enabled
- Pruning enabled
- Container image versions are explicitly pinned
