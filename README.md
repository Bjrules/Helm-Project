# Helm-Project
Helm the Helming way... (Notes and Project) :joy:


```
kubectl describe sa ebs-csi-controller-sa -n kube-system
```

## CONCEPTS
- HELM CHART | Package Used for Deploying, Modifying and Managing Application via Kubernetes cluster 
- HELM REPO | E.g special kind of Repositories where we can have multiple charts e.g bitnami repo has nginx, grafana and lots more..
- HELM RELEASE | An instance of a Helm Chart Application Deployment is a Helm Release

### Install HELM
```
curl -fsSL https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash
```
Some Useful helm commands.
