# GitLab Integration

## Create Personal Access Token

Required scope:

```text
read_repository
```

## Add Repository

```bash
argocd repo add https://gitlab.com/josephmj0303/argocd-app.git \
  --username YOUR_USERNAME \
  --password YOUR_TOKEN
```
