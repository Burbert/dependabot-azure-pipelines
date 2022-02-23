# Dependabot for Azure Pipelines
Use the pipeline definition within your Azure DevOps Project to utilize Dependabot to update your code.

## Variables
The main pipelines requires two pipeline variables:

- github_pat
  - to increase the GitHub API request limit, supply a personal access token
- pat
  - personal access token in Azure DevOps - this will be used to create PRs and so on.
