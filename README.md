📦 Project: CI-CD-2
🌐 Deployment Link:
https://iaman011.github.io/CI-CD-2/

📄 How Deployment Works
We use GitHub Actions to automate deployment of a static HTML website to GitHub Pages.

Deployment happens only from the main branch.

All development work is done in a dev branch.

After testing, changes are merged (or pushed) into the main branch to trigger the deployment workflow.

✅ Setup Deployment Workflow
Go to GitHub > Actions tab.

Search for a workflow template called "Static HTML" (or you can create your own static.yml).

Save the workflow file as .github/workflows/static.yml in your project repository.
