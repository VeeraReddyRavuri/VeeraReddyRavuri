<h1 align="center">Veera Reddy Ravuri</h1>

<p align="center">
  <b>Cloud / DevOps / SRE Engineer</b><br/>
  I build infrastructure that ships, scales, and stays observable.
</p>

<p align="center">
  <a href="https://veerareddyravuri.github.io">Portfolio</a> ·
  <a href="https://linkedin.com/in/veerareddyravuri">LinkedIn</a> ·
  <a href="https://veerareddyravuri.github.io/blog.html">Blog</a>
</p>

---

## Flagship System

**[aws-production-infra-blueprint](https://github.com/VeeraReddyRavuri/aws-production-infra-blueprint)**

Production-grade AWS infrastructure in Terraform: multi-tier VPC, NAT,
ALB, IAM boundaries, and remote state with S3 + DynamoDB locking.
Built to simulate real change management: modular, reproducible, and
designed to expose failure before it reaches production.

---

## What I build

Cloud infrastructure end-to-end: VPC architecture, IaC, containerised
workloads, serverless alerting pipelines, and Linux reliability tooling.
Every project here was built with a production mindset: real decisions,
documented tradeoffs, and metrics that prove it works.

---

## Shipped

| Project | What it does | Signal |
|---|---|---|
| [lambda-log-parser](https://github.com/VeeraReddyRavuri/lambda-log-parser) | Serverless log alerting pipeline built on Lambda, CloudWatch, and SNS | Two-path alert architecture |
| [bug-tracker-containerized-stack](https://github.com/VeeraReddyRavuri/bug-tracker-containerized-stack) | Full-stack app containerised with Docker + Nginx reverse proxy | 225MB → 120MB image (46% reduction) |
| [linux-reliability-toolkit](https://github.com/VeeraReddyRavuri/linux-reliability-toolkit) | Linux reliability scripts + Ansible-automated monitoring and alerting | ≤5 min detection latency |

---

## How I think

  Experience across production systems at HCLTech (Verizon) shaped how I approach systems:

- I assume systems will fail and design for detection and recovery
- I treat incidents as learning inputs, not one-time fixes
- I prefer simple, observable systems over complex, fragile ones
- I optimize for long-term maintainability, not short-term hacks

---

## Stack

`AWS` `Terraform` `Docker` `Ansible` `GitHub Actions` `Python` `Bash` `Linux` `PostgreSQL`

---

## Currently building

→ **Secure CI/CD Pipeline**
GitHub Actions pipeline with lint, test, Docker build, Trivy CVE scanning,
ECR push, GitOps manifest repo, CloudWatch validation, and automatic
rollback on health check failure. Blue/green deployments via ALB listener swap.

---

## Writing

- [Debugging Docker DNS in bridge networks — what the docs don't tell you](https://veerareddyravuri.github.io/blog.html#docker-dns-nginx-debugging)
- [Terraform state drift — what causes it and how to recover without panic](https://veerareddyravuri.github.io/blog.html#terraform-state-drift-recovery)
- [Linux Reliability Toolkit — Silent restart failure to automated recovery](https://veerareddyravuri.github.io/blog.html#linux-reliability-toolkit-deep-dive)

---

<p align="center">
  <a href="https://veerareddyravuri.github.io">veerareddyravuri.github.io</a>
</p>
