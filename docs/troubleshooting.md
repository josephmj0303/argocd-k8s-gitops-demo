# Deployment Guide

## Deploy Application

```bash
kubectl apply -f application.yaml
```

## Verify Application

```bash
kubectl get applications -n argocd
```

## Verify Pods

```bash
kubectl get pods -n myapp
```
