# GitOps Labs

## Lab 3
**Step One**
- Go to the gitops-keyvault in the Azure Portal
- Create two secrets with unique names
- Fill the value with something of your liking

**Step Two**
- Deploy your app folder, including base and overlays in the Lab3 folder

**Step Three**
- Create in the base folder a Secret manifest
- Create in the both overlays a Secret manifest
- Make sure you uphold the syntax of the ArgoCD Vault Plugin
- Each of the secret overlays should watch the different Keyvault secrets 

**Step Four**
- Add to your path manifests the configuration to pick up the secret
- This secret should be found in the container as LAB3_OUTPUT

**Step Five**
- Adjust your Application manifest so they watch the correct Kustomization overlays 

**Step Six**
- Push your branch and changes to the repository
- Create a Pull Request towards the main branch
- Let your peers review
- Validate your app in ArgoCD
- Check your webapps in your browser


If you are stuck, ask for help or check the solution:
<details>
   <summary><b>Solution</b></summary>
        <a href="https://github.com/cinqict/gitops-workshop/tree/lab3-solution">Check Lab 3 Solution</a>
</details>
