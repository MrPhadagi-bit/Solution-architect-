# AWS Solution Architect Project Portfolio

This repository is a structured portfolio of hands-on AWS projects. Each project is documented in Markdown, paired with a PDF manual, and has room for screenshots or exported visuals.

It is organized to make uploads and navigation easy on GitHub while keeping every project self-contained.

## Repository Structure

Each project lives in its own folder inside `projects/`.

```text
projects/
  01-host-a-website-on-amazon-s3/
    README.md
    pdf/
      manual.pdf
    images/
  02-cloud-security-with-aws-iam/
    README.md
    pdf/
    images/
templates/
  project-template.md
```

## What Goes In Each Project Folder

- `README.md`: the written project documentation
- `pdf/manual.pdf`: the project manual or exported lab PDF
- `images/`: screenshots used inside the write-up

Use [templates/project-template.md](templates/project-template.md) when creating or updating a project write-up.

## Project Catalog

| No. | Project | Link |
| --- | --- | --- |
| 01 | Host a Website on Amazon S3 | [Open](projects/01-host-a-website-on-amazon-s3/README.md) |
| 02 | Cloud Security with AWS IAM | [Open](projects/02-cloud-security-with-aws-iam/README.md) |
| 03 | Build a Virtual Private Cloud | [Open](projects/03-build-a-virtual-private-cloud/README.md) |
| 04 | VPC Traffic Flow and Security | [Open](projects/04-vpc-traffic-flow-and-security/README.md) |
| 05 | Creating a Private Subnet | [Open](projects/05-creating-a-private-subnet/README.md) |
| 06 | Launching VPC Resources | [Open](projects/06-launching-vpc-resources/README.md) |
| 07 | Testing VPC Connectivity | [Open](projects/07-testing-vpc-connectivity/README.md) |
| 08 | VPC Peering | [Open](projects/08-vpc-peering/README.md) |
| 09 | VPC Monitoring with Flow Logs | [Open](projects/09-vpc-monitoring-with-flow-logs/README.md) |
| 10 | Access S3 from a VPC | [Open](projects/10-access-s3-from-a-vpc/README.md) |
| 11 | VPC Endpoints | [Open](projects/11-vpc-endpoints/README.md) |
| 12 | Aurora Database with EC2 | [Open](projects/12-aurora-database-with-ec2/README.md) |
| 13 | Connect a Web App with Aurora | [Open](projects/13-connect-a-web-app-with-aurora/README.md) |
| 14 | Load Data into DynamoDB | [Open](projects/14-load-data-into-dynamodb/README.md) |
| 15 | Query Data with DynamoDB | [Open](projects/15-query-data-with-dynamodb/README.md) |
| 16 | Cloud Security with AWS IAM | [Open](projects/16-cloud-security-with-aws-iam/README.md) |
| 17 | Encrypt Data with AWS KMS | [Open](projects/17-encrypt-data-with-aws-kms/README.md) |
| 18 | Threat Detection with GuardDuty | [Open](projects/18-threat-detection-with-guardduty/README.md) |
| 19 | Secure Secrets with Secrets Manager | [Open](projects/19-secure-secrets-with-secrets-manager/README.md) |
| 20 | Build a Security Monitoring System | [Open](projects/20-build-a-security-monitoring-system/README.md) |
| 21 | Website Delivery with CloudFront | [Open](projects/21-website-delivery-with-cloudfront/README.md) |
| 22 | APIs with Lambda + API Gateway | [Open](projects/22-apis-with-lambda-api-gateway/README.md) |
| 23 | Fetch Data with AWS Lambda | [Open](projects/23-fetch-data-with-aws-lambda/README.md) |
| 24 | Build a Three-Tier Web App | [Open](projects/24-build-a-three-tier-web-app/README.md) |
| 25 | Launch a Kubernetes Cluster | [Open](projects/25-launch-a-kubernetes-cluster/README.md) |
| 26 | Set Up Kubernetes Deployment | [Open](projects/26-set-up-kubernetes-deployment/README.md) |
| 27 | Create Kubernetes Manifests | [Open](projects/27-create-kubernetes-manifests/README.md) |
| 28 | Deploy Backend with Kubernetes | [Open](projects/28-deploy-backend-with-kubernetes/README.md) |
| 29 | Set Up a Web App in the Cloud | [Open](projects/29-set-up-a-web-app-in-the-cloud/README.md) |
| 30 | Connect a GitHub Repo with AWS | [Open](projects/30-connect-a-github-repo-with-aws/README.md) |
| 31 | Secure Packages with CodeArtifact | [Open](projects/31-secure-packages-with-codeartifact/README.md) |
| 32 | Continuous Integration with CodeBuild | [Open](projects/32-continuous-integration-with-codebuild/README.md) |
| 33 | Deploy a Web App with CodeDeploy | [Open](projects/33-deploy-a-web-app-with-codedeploy/README.md) |
| 34 | Build a CI/CD Pipeline with AWS | [Open](projects/34-build-a-cicd-pipeline-with-aws/README.md) |
| 35 | Create S3 Buckets with Terraform | [Open](projects/35-create-s3-buckets-with-terraform/README.md) |

## Upload Workflow

For each new project:

1. Upload the project PDF to the matching `pdf/` folder as `manual.pdf`.
2. Add screenshots to the matching `images/` folder.
3. Replace the starter content in that project's `README.md`.
4. Follow the format from [templates/project-template.md](templates/project-template.md).

## Notes

- Project `02` and project `16` intentionally share the same title because both were included in your original project list.
- The root-level legacy Markdown files from the earlier repo history are still preserved.
