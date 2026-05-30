# Troubleshooting

## ArgoCD UI Not Accessible

Use:

```bash
kubectl port-forward --address 0.0.0.0 \
svc/argocd-server 8080:443 -n argocd
```

---

## GitLab Authentication Error

Ensure:

- Personal Access Token is valid
- Token has read_repository permission
- Correct GitLab username is used

---

## Pods Not Running

Check:

```bash
kubectl describe pod <pod-name> -n myapp
```

View logs:

```bash
kubectl logs <pod-name> -n myapp
```
