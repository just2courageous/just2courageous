# Courage Erhabor

**DevOps Engineer** focused on **AWS** projects and production style delivery.

✅ **Open to DevOps roles (2026).**

## 🔗 Links
- **Website:** https://courageerhabor.com
- **GitHub (GitHub):** https://github.com/just2courageous
- **LinkedIn (professional network):** https://linkedin.com/in/courageerhabor/
- **Email:** erhacour@gmail.com

## 🚀 Featured Projects
| Project | What it proves | Stack | Demo |
| --- | --- | --- | --- |
| [gg-rollouts-hpa](https://github.com/just2courageous/gg-rollouts-hpa) | Progressive delivery + autoscaling on Kubernetes | AWS (Amazon Web Services) EKS, Argo Rollouts, HPA | Planned (coming soon) |
| [gg-logging-cloudwatch](https://github.com/just2courageous/gg-logging-cloudwatch) | Centralized logging with secure auth | Fluent Bit (log shipping), CloudWatch Logs, IRSA, OIDC | Planned (coming soon) |
| [gg-ansible-ec2](https://github.com/just2courageous/gg-ansible-ec2) | Infrastructure automation on AWS (Amazon Web Services) | Terraform, EC2, Ansible | Planned (coming soon) |
| [gg-eks-terraform](https://github.com/just2courageous/gg-eks-terraform) | Full EKS build with IaC | Terraform , VPC, IAM | Planned (coming soon) |


## 🧰 Tech I use
- **AWS:** EKS, EC2, ECR, IAM, CloudWatch
- **Kubernetes:** Deployments (workloads), Services (networking), Ingress (routing), HPA
- **IaC:** Terraform
- **CI/CD :** GitHub Actions
- **GitOps:** Argo CD, Argo Rollouts
- **Observability:** Prometheus, Grafana, CloudWatch Logs (logging)

## 🧩 How my projects connect (end-to-end DevOps flow)

* **Terraform** provisions the foundation: **VPC + EKS + IAM + OIDC**
* **kubectl / Helm** deploy platform add-ons and workloads to the cluster
* **GitHub Actions ** builds and ships changes (pipeline) to support repeatable deployments
* **Argo CD** syncs Kubernetes manifests from GitHub to the cluster (GitOps)
* **Argo Rollouts + HPA** handle progressive delivery (canary) and autoscaling for the application
* **Fluent Bit → CloudWatch Logs [Amazon CloudWatch Logs]** centralizes cluster logging using **IRSA** (no static keys)

**Projects in this chain:**
* **gg-eks-terraform** → foundation (EKS + OIDC + IRSA)
* **gg-rollouts-hpa** → progressive delivery + autoscaling
* **gg-logging-cloudwatch** → centralized logging with IRSA
* **gg-ansible-ec2** → automation on EC2
* **green-guard** → umbrella repo tying the portfolio together


## 📌 What I’m doing now
- Building portfolio grade DevOps projects with proof: **diagrams**, **runbooks**, **screenshots**, and **demo videos**.
