# Architecture

This project follows a GitOps-based Kubernetes deployment workflow using ArgoCD.

## Components

- GitLab Repository
- ArgoCD
- Kubernetes Cluster
- Deployment
- Service

## Workflow

1. Kubernetes manifests are stored in GitLab
2. ArgoCD watches the repository
3. ArgoCD synchronizes manifests automatically
4. Kubernetes deploys the application
5. Changes pushed to Git are reflected in the cluster
