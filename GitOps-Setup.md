# GitOps Workshop

## Requirements
- Azure Account (https://portal.azure.com/)
- GitHub Account (https://github.com/)
- Azure CLI (https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Kubectl (https://kubernetes.io/docs/tasks/tools/)

## Setup
- Contact dion.simon@cinqict.nl to request access to the Azure AD

- Clone this repo and create your branch
  - git clone https://github.com/cinqict/gitops-workshop.git
  - git switch -c gitops-<yourname>

- Login onto Azure via Azure CLI:
  - az login --use-device-code

- Update Kubeconfig:
  - az aks get-credentials --resource-group rg-dionsimon-devops --name gitops-aks

## Links
- Workshop Repo (https://github.com/cinqict/gitops-wokrkshop)
- GitOps Image (https://hub.docker.com/repository/docker/bahqiplor/cinq-gitops-workshop/general)

## Git commands
- git commit -m "Example Comment"
- git push --set-upstream origin gitops-yourname

## Kubectl commands
- kubectl port-forward svc/service-name -n namespace local-port:aks-port
- kubectl get pods -n namespace

## K8s Docs
- Pod: (https://kubernetes.io/docs/concepts/workloads/pods/)
- Service: (https://kubernetes.io/docs/concepts/services-networking/service/)
- Application: (https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/)
- Kustomize: (https://www.densify.com/kubernetes-tools/kustomize/)
- Argocd Vault plugin: (https://argocd-vault-plugin.readthedocs.io/en/stable/)
