    Each app each driver for the rest of deployments. For example, app-1.yaml in this folder points to ../app-1/ terraorm configuration where we configure our deployments, services, network and other resources.


---
## Configuration

Change the repo url. This is the url of this repo.

```yaml
12 |     repoURL: https://github.com/reddddddddd/devops-cd.git
```

---

## Basic Commands

To delete application by running kubectl delete -f application.yaml (This application.yaml resides in the infrastructure repo)
```yaml
finalizers:
    - resources-finalizer.argocd.argoproj.io
```
