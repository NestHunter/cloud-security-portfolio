# Cloud Security Portfolio

This repository is the central hub for my AWS and cloud security work — hands-on labs, architecture projects, and technical write-ups built while pursuing the Cloud Security Engineer path.

## Focus Areas

- AWS architecture, networking, and security design
- Serverless and event-driven application patterns
- Infrastructure as Code with Terraform
- Python for cloud automation and tooling
- Secure, scalable cloud environment design

---

## Active Repositories

### [aws-saa-labs](https://github.com/NestHunter/aws-saa-labs)

Structured hands-on lab repository covering AWS Solutions Architect Associate topics. Each lab is documented in its own folder with a detailed README.

**Current labs:**

**Networking & VPC**
- [Enabling Outbound Internet Access from a Private Subnet with a NAT Gateway](https://github.com/NestHunter/aws-saa-labs/blob/main/labs/private-subnet-nat-gateway/README.md) — NAT Gateway placement, route table configuration, and security group design for private subnet outbound access.
- [Network Evaluation Challenge — VPC Troubleshooting Skills Assessment](https://github.com/NestHunter/aws-saa-labs/blob/main/labs/network-evaluation-challenge/README.md) — Multi-layer VPC diagnosis: inaccessible EC2 instance, misconfigured security group, missing private subnet route. Covers correct production architecture vs. quick workarounds.

**Serverless & Compute**
- [Connect a Lambda Function to a VPC](https://github.com/NestHunter/aws-saa-labs/blob/main/labs/connect-lambda-to-vpc/README.md) — Lambda VPC attachment, NAT Gateway requirements, ENI IAM permissions, and the full Lambda → EC2 → S3 workflow.
- [Fix an API Gateway GET Method Using Lambda Proxy Integration](https://github.com/NestHunter/aws-saa-labs/blob/main/labs/api-gateway-lambda-proxy-fix/README.md) — Troubleshooting a broken API Gateway integration after a Swagger import; recreating the GET method with correct Lambda proxy configuration.
- [Build a Serverless Web Application (S3, API Gateway, Lambda, SQS, DynamoDB)](https://github.com/NestHunter/aws-saa-labs/blob/main/labs/serverless-web-application/README.md) — End-to-end serverless application: S3 static frontend → API Gateway → producer Lambda → SQS → consumer Lambda → DynamoDB.

**Storage**
- [Amazon EBS Volumes](https://github.com/NestHunter/aws-saa-labs/blob/main/labs/ebs-volume-lab/README.md) — Full EBS lifecycle: create, attach, format, mount, persist via fstab, snapshot, and cross-AZ restore.

**Troubleshooting**
- [Troubleshooting an Application Load Balancer and CloudFormation Stack](https://github.com/NestHunter/aws-saa-labs/blob/main/troubleshooting/alb-cloudformation-troubleshooting.md) — Diagnosing and fixing a broken ALB deployment: Auto Scaling Group attachment, subnet placement, and security group rules.

---

## Planned Projects

| Project | Focus Area | Status |
|---|---|---|
| [AWS SAA Labs](https://github.com/NestHunter/aws-saa-labs) | VPC, networking, serverless, storage, compute | In Progress |
| Secure S3 Static Site | S3, bucket policies, encryption, hosting | Planned |
| Terraform AWS VPC | Networking, Infrastructure as Code, security groups | Planned |
| Three-Tier AWS Architecture | Secure architecture design, EC2, load balancing, databases | Planned |

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/deandre-wilson-939217141)
- [CyberNest](https://cybernesthub.com/)
