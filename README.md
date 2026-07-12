# KT

This repository includes an Azure DevOps YAML pipeline definition.

## Azure DevOps pipeline

Use `azure-pipelines.yml` when creating a pipeline in Azure DevOps from this GitHub repository.

### How to connect it

1. Push this repository to GitHub.
2. In Azure DevOps, go to **Pipelines** > **New pipeline**.
3. Select **GitHub** as the code source and authorize Azure DevOps if prompted.
4. Choose this repository.
5. Select **Existing Azure Pipelines YAML file**.
6. Choose `/azure-pipelines.yml`.
7. Save and run the pipeline.

The included pipeline runs on `ubuntu-latest`, checks out the repository, and validates that Azure DevOps can access the source files.
