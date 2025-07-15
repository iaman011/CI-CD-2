📦 Project: CI-CD-2
🌐 Deployment Link:
https://iaman011.github.io/CI-CD-2/

📑 Deployment Overview
Deployment happens only from the main branch.

All development work is done in a separate dev branch.

After making and testing changes in dev, we create a Pull Request (PR) to merge those changes into main.

Once the PR is reviewed and merged, the GitHub Actions workflow (static.yml) automatically deploys the latest code to GitHub Pages.

✅ Setup Deployment Workflow
Go to GitHub > Actions tab.

Search for a workflow template called "Static HTML" (or you can create your own static.yml).

Save the workflow file as .github/workflows/static.yml in your project repository.

```
Open a Pull Request (PR)

Go to your repository on GitHub.

Click Compare & pull request next to the dev branch.

Review the changes.

Assign reviewers if needed.

Merge the PR into main after approval.

## GitHub Actions Trigger

After merging, a push event occurs on the main branch.

This triggers the static.yml GitHub Actions workflow.

The site is deployed automatically to GitHub Pages.
