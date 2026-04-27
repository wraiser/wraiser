# 👋 Hi, I'm wraiser

**Infrastructure Engineer × AI Automation × Indie Developer**

---

## 🧑‍💻 About Me

- 🛠 **Specialty**: AWS × Terraform × CI/CD automation × Python tooling
- 🌐 **Working hours**: JST (UTC+9). Comfortable with async work via Slack / Linear / GitHub PRs.
- 🚀 Building production-ready infrastructure modules and lightweight automation tools.

---

## 🛠 Tech Stack

### Infrastructure & Cloud

![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

### App Development

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)

### AI & Automation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?style=flat&logo=google&logoColor=white)

---

## 🚀 Featured Projects

### [terraform-aws-starter-modules](https://github.com/wraiser/terraform-aws-starter-modules)

> **Production-ready Terraform modules for AWS (VPC, ALB, ECS Fargate) with full CI validation.**

A minimal, production-ready Terraform module set covering the most common AWS infrastructure patterns. Designed as a clean starting point for small-to-mid-sized workloads.

- **VPC module**: multi-AZ public/private subnets, IGW, conditional NAT Gateways
- **ALB module**: internet-facing Application Load Balancer with Fargate-ready target groups
- **ECS Fargate module**: cluster with Container Insights, IAM execution role, CloudWatch logs
- **End-to-end example** wiring all three modules together
- **GitHub Actions CI**: matrix running `fmt`, `validate` across every module + example

`Terraform >= 1.5` `AWS Provider >= 6.0` `Multi-AZ by default` `Least-privilege IAM`

### [terraform-github-actions](https://github.com/wraiser/terraform-github-actions)

> **Reusable GitHub Actions for Terraform on AWS.**

Three composable actions that cover the day-one CI needs of any Terraform repository:

- `terraform-checks` — `fmt -check`, `init -backend=false`, `validate`
- `terraform-plan-on-pr` — `terraform plan` via OIDC, posts result as PR comment
- `terraform-security` — `tflint` + Checkov scan, uploads SARIF to Code Scanning

Pairs naturally with `terraform-aws-starter-modules`. Self-tested in CI.

---

## 💼 Open for Freelance Work

Available for AWS infrastructure, Terraform, CI/CD, and lightweight web app projects.

- **Find me on**: [Upwork](https://www.upwork.com/) / [Lancers](https://www.lancers.jp/) / [Coconala](https://coconala.com/)

---

## 📊 GitHub Stats

![wraiser's GitHub stats](https://github-readme-stats.vercel.app/api?username=wraiser&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wraiser&layout=compact&theme=tokyonight&hide_border=true)
