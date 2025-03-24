# GitOps Labs

## Lab 2
**Step One**
- Deploy your app folder with manifests in the Lab2 folder
- Create a 'base' subfolder for the existing manifests

**Step Two**
- Create an 'overlays' subfolder. 
- Create within this subfolder two other subfolders, named after two different environments
- In each overlay folder should be a patch for both the pod and service manifests

**Step Three**
- Adjust the pod patches so they have an environment variable configured called 'OUTPUT'
- Adjust the service patches so they use different ports.

**Step Four**
- Time to use Kustomization to glue all manifests together
- In base folder define a Kustomization.yaml to create a base for Kustomization
- In each of the environment folders define a Kustomization.yaml so Kustomization can apply the patches correctly

**Step Five**
- Add a second app in the 'apps' folder and adjust them accordingly
- Both apps should be unique from each other
- Both apps should poll their environments
- Both apps should deploy in the correct namespace

**Step Six**
- Push your branch and changes to the repository
- Create a Pull Request towards the main branch
- Let your peers review
- Validate your app in ArgoCD
- Check your webapps in your browser

If you are stuck, ask for help or check the solution:
<details>
   <summary><b>Solution</b></summary>
        <a href="https://github.com/cinqict/gitops-workshop/tree/lab2-solution">Check Lab 2 Solution</a>
</details>
