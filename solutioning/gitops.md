Tools: Argocd
- You want to adopt the GitOps methodology.
    - https://argo-cd.readthedocs.io/en/stable/
- What is the best Continuous Deployment methodology on k8s?
- How do you get up external notification in ArgoCD?
    - You can use ArgoCD plugins to setup notification
        - https://argoproj.github.io/argo-workflows/plugin-directory/
        - The hermes and slack notification looks interesting
    - Better still you can use Argocd notification which supports more channels
        - https://argocd-notifications.readthedocs.io/en/stable/services/overview/