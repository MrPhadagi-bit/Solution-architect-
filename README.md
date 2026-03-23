<h1 align="center">AWS Solution Architect Project Portfolio</h1>

<p align="center">
  A structured collection of hands-on AWS projects covering networking, security, serverless, databases, containers, CI/CD, and infrastructure as code.
</p>

<p align="center">
  Maintained by <a href="https://github.com/MrPhadagi-bit">@MrPhadagi-bit</a>
</p>

## Overview

This repository is built as a portfolio of practical AWS labs and implementation projects. Each project has its own dedicated folder so the documentation, PDF manual, and screenshots stay together and are easy to review on GitHub.

This setup is designed to make the repo useful both as a learning archive and as a presentation-ready project portfolio.

## Highlights

- `35` structured AWS projects
- A `README.md` and `project.md` file in every project folder
- A `manual.pdf` file in every project folder
- Dedicated `images/` folders for screenshots and evidence
- Reusable template for consistent project write-ups

## Focus Areas

- AWS networking and VPC design
- IAM, KMS, GuardDuty, and Secrets Manager
- S3, CloudFront, Lambda, API Gateway, and DynamoDB
- Aurora, EC2, and three-tier application architecture
- Kubernetes deployments on AWS
- CodeArtifact, CodeBuild, CodeDeploy, and CI/CD pipelines
- Terraform-based AWS provisioning

## Repository Structure

```text
projects/
  01-host-a-website-on-amazon-s3/
    README.md
    project.md
    manual.pdf
    images/
  02-cloud-security-with-aws-iam/
    README.md
    project.md
    manual.pdf
    images/
  ...
templates/
  project-template.md
```

## Project Folder Standard

Every project folder follows the same pattern:

- `README.md` is the quick folder overview
- `project.md` is the main Markdown documentation file
- `manual.pdf` stores the project manual or lab export
- `images/` stores screenshots referenced in the write-up

Use [templates/project-template.md](templates/project-template.md) when writing or updating `project.md`.

## Project Catalog

| No. | Project | Link |
| --- | --- | --- |
| 01 | Host a Website on Amazon S3 | [Open](projects/01-host-a-website-on-amazon-s3/project.md) |
| 02 | Cloud Security with AWS IAM | [Open](projects/02-cloud-security-with-aws-iam/project.md) |
| 03 | Build a Virtual Private Cloud | [Open](projects/03-build-a-virtual-private-cloud/project.md) |
| 04 | VPC Traffic Flow and Security | [Open](projects/04-vpc-traffic-flow-and-security/project.md) |
| 05 | Creating a Private Subnet | [Open](projects/05-creating-a-private-subnet/project.md) |
| 06 | Launching VPC Resources | [Open](projects/06-launching-vpc-resources/project.md) |
| 07 | Testing VPC Connectivity | [Open](projects/07-testing-vpc-connectivity/project.md) |
| 08 | VPC Peering | [Open](projects/08-vpc-peering/project.md) |
| 09 | VPC Monitoring with Flow Logs | [Open](projects/09-vpc-monitoring-with-flow-logs/project.md) |
| 10 | Access S3 from a VPC | [Open](projects/10-access-s3-from-a-vpc/project.md) |
| 11 | VPC Endpoints | [Open](projects/11-vpc-endpoints/project.md) |
| 12 | Aurora Database with EC2 | [Open](projects/12-aurora-database-with-ec2/project.md) |
| 13 | Connect a Web App with Aurora | [Open](projects/13-connect-a-web-app-with-aurora/project.md) |
| 14 | Load Data into DynamoDB | [Open](projects/14-load-data-into-dynamodb/project.md) |
| 15 | Query Data with DynamoDB | [Open](projects/15-query-data-with-dynamodb/project.md) |
| 16 | Cloud Security with AWS IAM | [Open](projects/16-cloud-security-with-aws-iam/project.md) |
| 17 | Encrypt Data with AWS KMS | [Open](projects/17-encrypt-data-with-aws-kms/project.md) |
| 18 | Threat Detection with GuardDuty | [Open](projects/18-threat-detection-with-guardduty/project.md) |
| 19 | Secure Secrets with Secrets Manager | [Open](projects/19-secure-secrets-with-secrets-manager/project.md) |
| 20 | Build a Security Monitoring System | [Open](projects/20-build-a-security-monitoring-system/project.md) |
| 21 | Website Delivery with CloudFront | [Open](projects/21-website-delivery-with-cloudfront/project.md) |
| 22 | APIs with Lambda + API Gateway | [Open](projects/22-apis-with-lambda-api-gateway/project.md) |
| 23 | Fetch Data with AWS Lambda | [Open](projects/23-fetch-data-with-aws-lambda/project.md) |
| 24 | Build a Three-Tier Web App | [Open](projects/24-build-a-three-tier-web-app/project.md) |
| 25 | Launch a Kubernetes Cluster | [Open](projects/25-launch-a-kubernetes-cluster/project.md) |
| 26 | Set Up Kubernetes Deployment | [Open](projects/26-set-up-kubernetes-deployment/project.md) |
| 27 | Create Kubernetes Manifests | [Open](projects/27-create-kubernetes-manifests/project.md) |
| 28 | Deploy Backend with Kubernetes | [Open](projects/28-deploy-backend-with-kubernetes/project.md) |
| 29 | Set Up a Web App in the Cloud | [Open](projects/29-set-up-a-web-app-in-the-cloud/project.md) |
| 30 | Connect a GitHub Repo with AWS | [Open](projects/30-connect-a-github-repo-with-aws/project.md) |
| 31 | Secure Packages with CodeArtifact | [Open](projects/31-secure-packages-with-codeartifact/project.md) |
| 32 | Continuous Integration with CodeBuild | [Open](projects/32-continuous-integration-with-codebuild/project.md) |
| 33 | Deploy a Web App with CodeDeploy | [Open](projects/33-deploy-a-web-app-with-codedeploy/project.md) |
| 34 | Build a CI/CD Pipeline with AWS | [Open](projects/34-build-a-cicd-pipeline-with-aws/project.md) |
| 35 | Create S3 Buckets with Terraform | [Open](projects/35-create-s3-buckets-with-terraform/project.md) |

## How To Add A Project Manual

1. Open the matching project folder inside `projects/`.
2. Replace the `manual.pdf` file in that folder with your uploaded project PDF.
3. Add supporting screenshots to the `images/` directory.
4. Replace the starter content in that project's `project.md`.
5. Keep `README.md` as the quick folder overview.
6. Follow the structure in [templates/project-template.md](templates/project-template.md).

## Notes

- Project `02` and project `16` intentionally have the same title because both were part of the original project list.
- Legacy root-level Markdown files from the earlier repository history are still preserved.
- Each project folder now includes all three core files up front: `README.md`, `project.md`, and `manual.pdf`.
