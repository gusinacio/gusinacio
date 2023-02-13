# Infrastructure

These are my main devops and infrastructures technologies:

- 🏗️ Terraform
- 🏞️ Terragrunt
- 🐳 Docker
- 💪 Kubernetes
- 💻 Bash
- 🚀Pipelines
- 📁 Monorepos

My main cloud providers are:

- 💡️ AWS - Amazon Web Services
- 🔥 GCP - Google Cloud Platform

## Projects

- [nexxera-test](https://github.com/flametuner/nexxera-devops-test): test for a DevOps positon at Nexxera, the test was about fetching a daily update file from FTP and deploy it on Docker
- [kafka-docker](https://github.com/flametuner/kafka-docker): a way of running up kafka using docker-compose for Distributed Systems class.
- [crypto4all-infra](https://github.com/flametuner/crypto4all-infra): full infrastructure as code using Terragrunt/Terraform for Kubernetes Systems with GCP.

## Terraform modules

I also have a few Terraform Modules on Terraform Registry:

- [cloud-run-api](https://registry.terraform.io/modules/graphnode-technologies/cloud-run-api/gcp/latest): A easy way to create a cloud run api and keeping them warm using scheduler.
- [deployment-api](https://registry.terraform.io/modules/graphnode-technologies/deployment-api/kubernetes/latest): Create a deployment in Kubernetes with autoscaling, service and nginx ingress ready for production.
- [serverless-next-js](https://registry.terraform.io/modules/graphnode-technologies/serverless-nextjs/aws/latest): Use with [serverless-nextjs](https://github.com/serverless-nextjs/serverless-next.js) to create bucket, distribution and domain record in AWS and keep track of it.
- [registry](https://registry.terraform.io/modules/graphnode-technologies/registry/aws/latest): Create an ERC repository with easy cleanup policy.