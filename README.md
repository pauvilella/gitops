# GitOps

## Apply Changes to ArgoCD
With the correct context set, run the following command to apply changes to ArgoCD (this is an example, the specific file will vary depending on the resource to apply):
```bash
kubectl apply -n argocd -f argocd/projects/blog.yaml
```
