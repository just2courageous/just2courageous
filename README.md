# Courage Erhabor

**DevOps (Development and Operations) Engineer** focused on **AWS (Amazon Web Services)** projects and production style delivery.

✅ **Open to DevOps (Development and Operations) roles (2026).**

## 🔗 Links
- **Website:** https://courageerhabor.com
- **GitHub (GitHub):** https://github.com/just2courageous
- **LinkedIn (professional network):** https://linkedin.com/in/courageerhabor/
- **Email:** erhacour@gmail.com

## 🚀 Featured Projects
| Project | What it proves | Stack | Demo |
| --- | --- | --- | --- |
| [gg-rollouts-hpa](https://github.com/just2courageous/gg-rollouts-hpa) | Progressive delivery + autoscaling on Kubernetes (container orchestration) | AWS (Amazon Web Services) EKS (Elastic Kubernetes Service), Argo Rollouts (progressive delivery), HPA (Horizontal Pod Autoscaler) | Planned (coming soon) |
| [gg-logging-cloudwatch](https://github.com/just2courageous/gg-logging-cloudwatch) | Centralized logging with secure auth | Fluent Bit (log shipping), CloudWatch Logs (logging), IRSA (IAM Roles for Service Accounts), OIDC (OpenID Connect) | Planned (coming soon) |
| [gg-ansible-ec2](https://github.com/just2courageous/gg-ansible-ec2) | Infrastructure automation on AWS (Amazon Web Services) | Terraform (Infrastructure as Code), EC2 (Elastic Compute Cloud), Ansible (automation) | Planned (coming soon) |
| [gg-eks-terraform](https://github.com/just2courageous/gg-eks-terraform) | Full EKS (Elastic Kubernetes Service) build with IaC (Infrastructure as Code) | Terraform (Infrastructure as Code), VPC (Virtual Private Cloud), IAM (Identity and Access Management) | Planned (coming soon) |


## 🧰 Tech I use
- **AWS (Amazon Web Services):** EKS (Elastic Kubernetes Service), EC2 (Elastic Compute Cloud), ECR (Elastic Container Registry), IAM (Identity and Access Management), CloudWatch (logging/metrics)
- **Kubernetes (container orchestration):** Deployments (workloads), Services (networking), Ingress (routing), HPA (Horizontal Pod Autoscaler)
- **IaC (Infrastructure as Code):** Terraform (Infrastructure as Code)
- **CI/CD (Continuous Integration/Continuous Delivery):** GitHub Actions (automation)
- **GitOps (Git Operations):** Argo CD (continuous delivery), Argo Rollouts (progressive delivery)
- **Observability (monitoring/logging):** Prometheus (metrics), Grafana (dashboards), CloudWatch Logs (logging)

## 🧩 How my projects connect (end-to-end DevOps flow)

* **Terraform [Infrastructure as Code]** provisions the foundation: **VPC [Virtual Private Cloud] + EKS [Elastic Kubernetes Service] + IAM [Identity and Access Management] + OIDC [OpenID Connect]**
* **kubectl [Kubernetes Command Line Tool] / Helm [Helm Package Manager]** deploy platform add-ons and workloads to the cluster
* **GitHub Actions [Continuous Integration and Continuous Delivery]** builds and ships changes (pipeline) to support repeatable deployments
* **Argo CD [GitOps Continuous Delivery]** syncs Kubernetes manifests from GitHub to the cluster (GitOps [Git Operations])
* **Argo Rollouts [Progressive Delivery Controller] + HPA [Horizontal Pod Autoscaler]** handle progressive delivery (canary) and autoscaling for the application
* **Fluent Bit [Log Shipper] → CloudWatch Logs [Amazon CloudWatch Logs]** centralizes cluster logging using **IRSA [IAM Roles for Service Accounts]** (no static keys)

**Projects in this chain:**
* **gg-eks-terraform** → foundation (EKS + OIDC + IRSA)
* **gg-rollouts-hpa** → progressive delivery + autoscaling
* **gg-logging-cloudwatch** → centralized logging with IRSA
* **gg-ansible-ec2** → automation on EC2 [Elastic Compute Cloud] (separate automation track)
* **green-guard** → umbrella repo tying the portfolio together


## 📌 What I’m doing now
- Building portfolio grade DevOps (Development and Operations) projects with proof: **diagrams**, **runbooks**, **screenshots**, and **demo videos**.
