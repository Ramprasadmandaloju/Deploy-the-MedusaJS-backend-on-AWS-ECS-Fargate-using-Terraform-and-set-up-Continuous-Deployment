
# MedusaJS Backend Deployment on AWS ECS using Terraform & GitHub Actions

This project deploys the Medusa headless commerce backend using:
- Terraform
- AWS ECS with Fargate
- Docker
- GitHub Actions

## Folder Structure
- `medusa-server/`: Medusa backend app (placeholder)
- `terraform/`: Terraform infrastructure code
- `.github/workflows/`: GitHub Actions deployment pipeline

## Prerequisites
- AWS Account
- GitHub account
- Docker, Terraform, Node.js, AWS CLI

## How to Deploy
2. Configure AWS credentials: `aws configure`
3. Build and push Docker image (or let GitHub Actions do it)
4. Run `terraform init && terraform apply` in the `terraform/` folder
5. Push code to `main` branch to auto-deploy via GitHub Actions

## Clean Up
```bash
cd terraform
terraform destroy
```
