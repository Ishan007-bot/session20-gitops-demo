# session20-gitops-demo

GitOps demo for Session 20. Argo CD watches `app/` and keeps the `session20` namespace in sync.

- `app/` - Kubernetes manifests (Deployment + Service) synced by Argo CD
- `argocd/argocd-application.yaml` - the Argo CD Application, applied once with kubectl (kept outside `app/`)
