# terraform-cloud-infrastructure
Infrastructure as Code with Terraform Cloud
\n# Testing GitHub Integration
# Terraform Cloud Infrastructure

## Deployment Status
![Development](https://app.terraform.io/api/v2/organizations/YOUR_ORG/workspaces/github-dev/current-run/badge)
![Staging](https://app.terraform.io/api/v2/organizations/YOUR_ORG/workspaces/github-staging/current-run/badge)
![Production](https://app.terraform.io/api/v2/organizations/YOUR_ORG/workspaces/github-prod/current-run/badge)

## Overview
Infrastructure as Code managed through Terraform Cloud with GitHub integration.

### Workflow
1. Development changes pushed to `development` branch
2. Auto-deployed to development environment
3. PR to `staging` branch for staging deployment
4. PR to `main` branch for production deployment
5. Manual approval required for staging and production

### Environments
- **Development**: Auto-deploy on push
- **Staging**: Manual approval required
- **Production**: Manual approval + PR review required