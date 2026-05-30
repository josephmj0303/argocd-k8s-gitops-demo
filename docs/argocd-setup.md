# ArgoCD Setup

## Create Namespace

```bash
kubectl create namespace argocd
```

## Install ArgoCD

```bash
kubectl apply -n argocd -f \
https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

## Verify Installation

```bash
kubectl get pods -n argocd
```
