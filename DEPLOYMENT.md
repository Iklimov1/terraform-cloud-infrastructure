# Deployment Checklist

## Pre-Deployment
- [ ] Code reviewed and approved
- [ ] Tests passing
- [ ] Security scan completed
- [ ] Resource plan output reviewed

## Deployment Steps
1. Merge to target branch
2. Terraform Cloud runs plan
3. Review plan output
4. Approve apply (staging/prod)
5. Monitor deployment

## Post-Deployment
- [ ] Verify application health
- [ ] Check monitoring dashboards
- [ ] Update documentation
- [ ] Notify stakeholders