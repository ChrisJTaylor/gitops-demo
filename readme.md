```
argocd app create gitops-demo --repo https://github.com/ChrisJTaylor/gitops-demo.git --path development --dest-server https://kubernetes.default.svc --dest-namespace gitops-dev
```

```
argocd app create gitops-demo --repo https://github.com/ChrisJTaylor/gitops-demo.git --path production --dest-server https://kubernetes.default.svc --dest-namespace gitops-prd
```