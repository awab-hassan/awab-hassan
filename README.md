<!--
**awab-hassan/awab-hassan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<h1 align="center">Hi, I'm Awab 👋</h1>
<h3 align="center">Senior DevOps & Platform Engineer · CKA Certified · 3+ Years</h3>
<h4 align="center">Kubernetes · Jenkins · AWS · Terraform · ArgoCD · Istio</h4>

<p align="center">
  <a href="https://linkedin.com/in/awabhassannizami"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://awab-hassan.github.io"><img src="https://img.shields.io/badge/Portfolio-1D9E75?style=flat-square&logo=githubpages&logoColor=white"/></a>
  <a href="https://medium.com/@awabhassan"><img src="https://img.shields.io/badge/Medium-12100E?style=flat-square&logo=medium&logoColor=white"/></a>
  <a href="mailto:awabrajpoot88@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://www.credly.com/badges/40806cb9-ed58-40be-9edc-6893110f8952/public_url"><img src="https://img.shields.io/badge/CKA-Certified-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20Work-1D9E75?style=flat-square"/>
</p>

---

## About

Certified Kubernetes Administrator (CKA) and Senior DevOps & Platform Engineer with 3+ years building and operating cloud-native infrastructure for US engineering teams. I currently operate production Jenkins serving 2,000+ daily builds at 99.9% uptime, and run GitOps-driven Kubernetes platforms supporting 400+ microservices with ArgoCD and Istio.

I specialize in the boring, high-stakes problems most engineers avoid - keeping CI/CD reliable at scale, hardening Kubernetes in production, and turning fragile deployment pipelines into systems teams actually trust. Currently studying offensive security (HTB CPTS) on the side because understanding how systems break is how I build infrastructure that doesn't.

## Core Stack

```
Containers & Orchestration  │  Kubernetes (EKS, AKS, on-prem), Docker, Helm, ArgoCD, GitOps, Istio (mTLS)
CI/CD                       │  Jenkins (Job DSL, Pipeline DSL, Shared Libraries), GitHub Actions, GitLab CI
Cloud                       │  AWS (EKS, ECS, EC2, RDS, S3, Lambda, API Gateway, IAM, VPC), Azure (AKS), GCP
Infrastructure as Code      │  Terraform, Ansible, AWS CodePipeline / CodeBuild, CloudFormation
Observability               │  Prometheus, Grafana, Loki, Tempo, Jaeger, Kiali, ELK Stack
Supply-Chain Security       │  Cosign image signing, Kyverno admission policies, cluster hardening
Languages                   │  Bash, Python, YAML, Groovy, PowerShell
```

---

## Experience Highlights

**Senior DevOps & Platform Engineer (Jenkins / CI/CD)** · Upwork - Confidential US Client · Jan 2026 – Present
> Production Jenkins at 2,000+ daily builds, 99.9% uptime, 5+ engineering teams · Jenkins Job DSL & Shared Pipeline Libraries · 50+ standardized pipelines · onboarding from 2 days to under 1 hour · CI/CD governance and security hardening across the org

**Senior Kubernetes / Platform Engineer** · Upwork - Confidential US Client · Apr 2025 – Present *(Part-time since Jan 2026)*
> EKS, AKS, and on-prem Kubernetes clusters running 400+ microservices · ArgoCD-driven GitOps with rollback MTTR under 5 minutes · Istio service mesh with strict mTLS and zero-trust networking · LGTM observability stack (Prometheus, Grafana, Loki, Tempo, Jaeger, Kiali)

**AWS DevOps Engineer** · NinesArch · Sep 2024 – Sep 2025
> Architected AWS solutions (EKS, ECS, Lambda, API Gateway, RDS, ElastiCache, S3) achieving 99.99% availability · Terraform IaC reducing provisioning time by ~40% · CI/CD via AWS CodePipeline + CodeBuild + GitHub Actions · EC2→ECS migrations with Redis caching cutting response times by ~30% · zero-downtime daily deploys (up from weekly cycles)

**Freelance DevOps Engineer (AWS / Kubernetes)** · Self-employed · Sep 2023 – Sep 2024
> Multi-environment AWS infrastructure (ECS, EKS, EC2, RDS, S3) with Terraform and GitHub Actions · Stateful Docker/Kubernetes workloads with MySQL/PostgreSQL · Docker image supply-chain security with Cosign - signed at build, verified at deploy · Python/Bash automation across cloud operations

**DevOps Engineer** · GoCloud Pvt Ltd · Dec 2022 – Aug 2023
> Containerized e-commerce workloads on Kubernetes + Docker across AWS, DigitalOcean, and Linode · Terraform multi-cloud provisioning · AWS RDS (MySQL) management and tuning · CI/CD pipelines on Jenkins, GitHub Actions, and GitLab CI

---

## Portfolio Projects

### Kubernetes & Containers

| Repo | Description | Stack |
|------|-------------|-------|
| [eks-microservices-k8s-manifests](https://github.com/awab-hassan/16-eks-microservices-k8s-manifests) | Spring Boot microservice platform on EKS (eu-west-2) - 6 services, HPA, Redis, ECR helper, graceful shutdown | K8s · EKS · Spring · Redis |
| [kasm-workspaces-aws-eks](https://github.com/awab-hassan/09-kasmWorkspace-DEVOPS) | Kasm Workspaces deployment on AWS EKS - Kubernetes manifests, networking, persistent storage | EKS · K8s · AWS |
| [ecommerce-aws-eks](https://github.com/awab-hassan/01-ecommerce-DEVOPS) | E-Commerce application deployment on AWS EKS | EKS · K8s · AWS |
| [shinobi-cctv-k8s](https://github.com/awab-hassan/03-shinobiApplication-DEVOPS) | CCTV app on Kubernetes - NFS PersistentVolumes, MySQL, Secrets, Services | K8s · Docker · MySQL · NFS |
| [cattr-application-k8s](https://github.com/awab-hassan/04-cattrApplication-DEVOPS) | Cattr time-tracking app deployment on Kubernetes | K8s · Docker · MySQL |
| [lke-cluster-terraform](https://github.com/awab-hassan/02-linodeTerraform-DEVOPS) | LKE (Linode) Kubernetes cluster deployment with Terraform | LKE · Terraform · K8s |

### CI/CD Pipelines

| Repo | Description | Stack |
|------|-------------|-------|
| [ecs-amplify-github-actions](https://github.com/awab-hassan/31-ecs-amplify-github-actions-cicd) | End-to-end CI/CD with GitHub Actions deploying to ECS and AWS Amplify | GitHub Actions · ECS · Amplify |
| [cosign-policy-kyverno](https://github.com/awab-hassan/05-cosignPolicy-DEVOPS) | Cluster-wide image signing policy with Cosign + Kyverno - only signed images admitted | Cosign · Kyverno · K8s |

### Infrastructure as Code

| Repo | Description | Stack |
|------|-------------|-------|
| [dr-pilot-light-terraform](https://github.com/awab-hassan/29-dr-pilot-light-terraform) | AWS Pilot-Light Disaster Recovery - EC2 snapshots, dated AMI, Launch Template, scaled-to-zero ASG, HTTPS ALB, Route 53 failover | Terraform · AWS · DR |
| [ecs-fargate-stack-terraform](https://github.com/awab-hassan/33-ecs-fargate-stack-terraform) | ECS Fargate stack - backend service, Redis via Service Connect, ALB, EFS, SSM secrets, least-privilege IAM | Terraform · ECS Fargate |
| [aurora-mysql-platform-terraform](https://github.com/awab-hassan/24-aurora-mysql-platform-terraform) | Multi-AZ Aurora MySQL cluster - read-replica autoscaling, CloudWatch+SNS alarms, 3-hourly Lambda snapshot pipeline to S3 | Terraform · Aurora · Lambda |
| [api-gateway-rest-scaffold-terraform](https://github.com/awab-hassan/23-api-gateway-rest-scaffold-terraform) | Reusable Terraform module for AWS API Gateway REST APIs with Lambda integrations and custom authorizers | Terraform · API Gateway |
| [ecs-fargate-task-definitions](https://github.com/awab-hassan/30-ecs-fargate-task-definitions-terraform) | ECS Fargate task definitions with Terraform - reusable patterns for container workloads | Terraform · ECS |
| [secure-rds-mysql-terraform](https://github.com/awab-hassan/17-rds-mysql-terraform) | Secure RDS MySQL deployment - networking, parameter groups, backup automation, IAM | Terraform · RDS · AWS |
| [elasticache-redis-terraform](https://github.com/awab-hassan/34-elasticache-redis-terraform) | ElastiCache Redis provisioning on AWS with Terraform | Terraform · ElastiCache |
| [dynamodb-registry-terraform](https://github.com/awab-hassan/19-dynamodb-registry-terraform) | DynamoDB registry table with Terraform | Terraform · DynamoDB |
| [vpc-peering-cross-region](https://github.com/awab-hassan/28-VPCPEERING-SETUP-TERRAFORM) | Cross-region VPC peering setup with Terraform | Terraform · AWS · VPC |

### Serverless & Lambda

| Repo | Description | Stack |
|------|-------------|-------|
| [serverless-event-api](https://github.com/awab-hassan/15-serverless-api-dynamo-lambda) | Serverless event aggregation API - API Gateway, Lambda, DynamoDB | Lambda · DynamoDB · API GW |
| [cloudfront-cache-invalidator](https://github.com/awab-hassan/32-cloudfront-cache-invalidator-lambda) | CloudFront cache invalidator Lambda | Lambda · CloudFront |
| [cloudfront-cache-manager](https://github.com/awab-hassan/22-cloudfront-cache-manager-lambda) | CloudFront cache manager Lambda | Lambda · CloudFront |
| [lambda-dashboard-generator](https://github.com/awab-hassan/21-lambda-dashboard-generator) | Lambda CloudWatch dashboard generator | Lambda · CloudWatch |
| [cron-lambda-s3-config](https://github.com/awab-hassan/27-cron-lambda-s3-config) | Scheduled Lambda functions reading config from S3 | Lambda · S3 · EventBridge |
| [aws-lambda-iam-export-scripts](https://github.com/awab-hassan/26-aws-lambda-iam-export-scripts) | Lambda IAM export scripts for audit/inventory automation | Lambda · IAM · Python |
| [redis-connector-lambda](https://github.com/awab-hassan/35-redis-connector-lambda-terraform) | Lambda Redis connector deployed via Terraform | Lambda · Redis · Terraform |
| [vpc-peering-redis-connector](https://github.com/awab-hassan/20-vpc-peering-redis-connector) | VPC peering Redis connector for cross-VPC Lambda→Redis access | Lambda · VPC · Redis |
| [php-lambda-bref-scylladb](https://github.com/awab-hassan/18-php-lambda-bref-scylladb) | PHP Lambda using Bref runtime with ScyllaDB backend | Lambda · Bref · ScyllaDB |

### Applications & Deployments

| Repo | Description | Stack |
|------|-------------|-------|
| [nextjs-aws-ecs](https://github.com/awab-hassan/11-nextJS-DEVOPS) | NextJS application deployment on AWS ECS | NextJS · ECS · Docker |
| [python-discord-exporter-ecs](https://github.com/awab-hassan/07-pythonProject-DEVOPS) | Python Discord chat exporter containerized and deployed to AWS ECS | Python · ECS · Docker |
| [nodejs-aws-ec2](https://github.com/awab-hassan/08-nodeJS-DEVOPS) | NodeJS application deployment on AWS EC2 | NodeJS · EC2 · AWS |
| [python-elastic-beanstalk](https://github.com/awab-hassan/10-elasticBeanStalk-DEVOPS) | Python application deployment on AWS Elastic Beanstalk | Python · Elastic Beanstalk |
| [powermta-digitalocean](https://github.com/awab-hassan/06-powerMTA-DEVOPS) | PowerMTA dockerization and deployment on DigitalOcean | Docker · DigitalOcean |
| [nginx-s3-config-sync](https://github.com/awab-hassan/13-nginx-s3-config-sync) | NGINX S3 config sync - dynamic configuration management | NGINX · S3 · Bash |
| [php-fpm-memory-diagnostic](https://github.com/awab-hassan/14-php-fpm-memory-diagnostic) | PHP-FPM memory diagnostic tooling | PHP · Linux · Diagnostics |

### Case Studies

| Repo | Description |
|------|-------------|
| [senior-k8-engineer-casestudies](https://github.com/awab-hassan/36-senior-k8-engineer-casestudies) | 28 documented production case studies from senior Kubernetes platform work - ArgoCD GitOps across 400+ microservices, Istio mTLS rollout/rollback, LGTM observability stack, multi-region migrations. Client identifiers genericized for confidentiality. |

---

## Certifications

| Certification | Issuer | Valid |
|---------------|--------|-------|
| [Certified Kubernetes Administrator (CKA)](https://www.credly.com/badges/40806cb9-ed58-40be-9edc-6893110f8952/public_url) | The Linux Foundation | Jun 2025 – Jun 2027 |

---

<p align="center">
  <i>Available for remote full-time roles, contracts, and advisory engagements · DevOps · Platform Engineering · SRE · Cloud Infrastructure</i><br/>
  <i>US · EU · UK · Gulf time zones</i>
</p>
