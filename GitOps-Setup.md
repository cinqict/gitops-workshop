# GitOps Workshop

## Requirements
- Azure Account (https://portal.azure.com/)
- GitHub Account (https://github.com/)
- Azure CLI (https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Kubectl (https://kubernetes.io/docs/tasks/tools/)

## Setup
- Contact dion.simon@cinqict.nl to:
  - Request access to the Azure AD 
  - Request Contributor access to the GitHub Repo

- Clone this repo
  - git clone https://github.com/cinqict/gitops-workshop.git

## Links
- Workshop Repo (https://github.com/cinqict/gitops-workshop)
- GitOps Image (https://hub.docker.com/repository/docker/bahqiplor/cinq-gitops-workshop/general)

## Git commands
- git branch gitops-yourname
- git commit -m "Example Comment"
- git push --set-upstream origin gitops-yourname

## Kubectl commands
- kubectl port-forward svc/service-name -n namespace local-port:aks-port