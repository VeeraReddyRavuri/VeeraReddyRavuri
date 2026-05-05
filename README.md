<h1 align="center">Veera Reddy Ravuri</h1>

<p align="center">
  <b>Cloud / DevOps / SRE Engineer</b><br/>
  Production systems, deployment safety, and infrastructure reliability.
</p>

<p align="center">
  <a href="https://veerareddyravuri.github.io">Portfolio</a> ·
  <a href="https://veerareddyravuri.github.io/resume.html">Resume</a> ·
  <a href="https://linkedin.com/in/veerareddyravuri">LinkedIn</a> ·
  <a href="https://veerareddyravuri.github.io/blog.html">Blog</a>
</p>

---

## Flagship System

**[secure-cicd-gitops-pipeline](https://github.com/VeeraReddyRavuri/secure-cicd-gitops-pipeline)**

Production-grade GitOps CI/CD pipeline with canary deployments, ALB traffic shifting, and automated rollback within ~2 minutes based on runtime failure-rate validation.

**Key signals:**
- Blue/Green + Canary deployment strategy (controlled blast radius)
- Failure-rate–based rollback (not just health checks)
- Trivy security gating blocking CRITICAL CVEs
- GitOps manifest repo with state-consistent rollback

---

## What I Do

I design and operate production-like systems with a focus on:

- Deployment safety (CI/CD, rollback, failure isolation)
- Infrastructure as Code (Terraform, reproducible environments)
- Observability and alerting (CloudWatch, structured logging)
- Incident-driven reliability (RCA, failure simulation, recovery automation)

---

## How I think

  Experience across production systems at HCLTech (Verizon) shaped how I approach systems:

- I assume systems will fail and design for detection and recovery
- I treat incidents as learning inputs, not one-time fixes
- I prefer simple, observable systems over complex, fragile ones
- I optimize for long-term maintainability, not short-term hacks

---

## Shipped

| Project | Impact |
|---|---|
| [secure-cicd-gitops-pipeline](https://github.com/VeeraReddyRavuri/secure-cicd-gitops-pipeline) | Automated rollback within ~2 minutes using failure-rate validation + ALB traffic shifting |
| [aws-production-infra-blueprint](https://github.com/VeeraReddyRavuri/aws-production-infra-blueprint) | 14-resource AWS infra with Terraform + remote state + drift recovery |
| [bug-tracker-containerized-stack](https://github.com/VeeraReddyRavuri/bug-tracker-containerized-stack) | 46% image reduction + resolved real DNS load-balancing bug |
| [lambda-log-parser](https://github.com/VeeraReddyRavuri/lambda-log-parser) | Event-driven alerting pipeline with CloudWatch + SNS (validated delivery) |
| [linux-reliability-toolkit](https://github.com/VeeraReddyRavuri/linux-reliability-toolkit) | ≤5 min failure detection + automated recovery via systemd |

---

## Production Experience

Software Engineer at HCLTech (Verizon billing platform):

- Prevented ~$200K revenue impact affecting 24,700+ customers via production debugging
- Reduced MTTR by 30% across 100+ incidents through structured RCA
- Automated regression cycles from 3 days → 4 hours

This directly informs how I design systems here — focused on failure, recovery, and operational reality.

---

## Stack

`AWS` `Terraform` `GitHub Actions` `Docker` `Linux` `Python` `Bash` `GitOps` `Kubernetes (in progress)` `ArgoCD (in progress)` `Ansible` `PostgreSQL`

---

## Currently building

**Kubernetes Production Readiness Lab**

End-to-end Kubernetes stack with GitOps, observability, and failure-driven validation:

- Deploying microservices with probes, resource limits, HPA, and persistent storage
- GitOps via ArgoCD with auto-sync and self-healing cluster state
- Full observability stack (Prometheus, Grafana, AlertManager)
- Enforcing production controls: RBAC, NetworkPolicies, PodDisruptionBudgets
- Running chaos scenarios (pod crash, CPU spike, network partition, node drain, config drift)
- Validating RED/USE metrics during failure conditions

→ Goal: simulate real production failure conditions and validate system resilience end-to-end.

---

## Writing

- [Incident Report — Runtime Failure After a Perfect CI Run](https://veerareddyravuri.github.io/blog.html#run-time-failure-after-ci-run)
- [Debugging Docker DNS in bridge networks — what the docs don't tell you](https://veerareddyravuri.github.io/blog.html#docker-dns-nginx-debugging)
- [Terraform state drift — what causes it and how to recover without panic](https://veerareddyravuri.github.io/blog.html#terraform-state-drift-recovery)
- [Linux Reliability Toolkit — Silent restart failure to automated recovery](https://veerareddyravuri.github.io/blog.html#linux-reliability-toolkit-deep-dive)

---

<p align="center">
  <a href="https://veerareddyravuri.github.io">veerareddyravuri.github.io</a>
</p>
