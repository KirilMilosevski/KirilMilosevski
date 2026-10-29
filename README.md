<p align="center">
  <img src="assets/matrix-banner.svg" alt="Kiril Milosevski, DevOps Engineer, with DevOps tool names raining down Matrix-style" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=kubectl+get+pods+-A;terraform+plan;cdk+deploy;argocd+app+sync+platform&font=Fira%20Code&color=00FF41&background=0D1117&center=true&vCenter=true&width=640&height=50&pause=900" alt="Terminal typing: kubectl get pods, terraform plan, cdk deploy, argocd app sync" />
</p>

<p align="center">
  <img src="assets/incident.svg" alt="Incident card cycling from triggered to acknowledged to resolved: coffee level low, espresso deployed" />
</p>

# Hi, I'm Kiril

**DevOps Engineer in Skopje** — I design, automate, and operate reliable cloud infrastructure on **AWS** and **Azure**.

I build platforms with Terraform and **AWS CDK**, ship with CI/CD and GitOps, and care about observability, security gates, and removing manual toil.

```hcl
resource "engineer" "kiril" {
  name     = "Kiril Milosevski"
  role     = "DevOps Engineer"
  location = "Skopje, North Macedonia"

  clouds = ["aws", "azure"]
  iac    = ["terraform", "aws-cdk"]
  gitops = ["argocd", "github-actions", "gitlab-ci"]

  lifecycle {
    prevent_destroy = true
    ignore_changes  = [sleep_schedule]
  }
}
```

## What I do

- Design and operate AWS and Azure infrastructure for SaaS / platform workloads
- Infrastructure as Code with **Terraform** and **AWS CDK**
- CI/CD with GitHub Actions and GitLab CI (OIDC, image scanning, safe rollouts)
- Containers and orchestration: Docker, ECS, Kubernetes, Helm, Argo CD
- Observability: Grafana, Prometheus, Alloy, Loki, CloudWatch, Datadog
- Networking and access: DNS, VPN, Cloudflare, IAM / managed identities
- Security in the pipeline: Trivy, Gitleaks, least-privilege IAM

## Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws&theme=dark" alt="AWS" />
  <img src="https://skillicons.dev/icons?i=azure&theme=dark" alt="Azure" />
  <img src="https://skillicons.dev/icons?i=terraform&theme=dark" alt="Terraform" />
  <img src="https://skillicons.dev/icons?i=kubernetes&theme=dark" alt="Kubernetes" />
  <img src="assets/icons/argocd.svg" width="48" height="48" alt="Argo CD" />
  <img src="assets/icons/helm.svg" width="48" height="48" alt="Helm" />
  <img src="https://skillicons.dev/icons?i=docker&theme=dark" alt="Docker" />
  <img src="https://skillicons.dev/icons?i=githubactions&theme=dark" alt="GitHub Actions" />
  <img src="https://skillicons.dev/icons?i=gitlab&theme=dark" alt="GitLab" />
  <img src="https://skillicons.dev/icons?i=grafana&theme=dark" alt="Grafana" />
  <img src="https://skillicons.dev/icons?i=prometheus&theme=dark" alt="Prometheus" />
  <img src="https://skillicons.dev/icons?i=cloudflare&theme=dark" alt="Cloudflare" />
  <img src="https://skillicons.dev/icons?i=linux&theme=dark" alt="Linux" />
  <img src="https://skillicons.dev/icons?i=bash&theme=dark" alt="Bash" />
</p>

```text
$ kubectl get skills
NAME             READY   STATUS
terraform        1/1     Running
aws-cdk          1/1     Running
kubernetes       1/1     Running
argocd           1/1     Running
observability    1/1     Running
```

<details>
<summary>Full skills breakdown</summary>

| Category | Tools |
|---|---|
| Cloud | AWS (EC2, ECS, ECR, Lambda, IAM, VPC, CloudFront, WAF, SSM) · Azure (Function Apps, APIM, Front Door, Cosmos DB, Key Vault, Managed Identity, Service Bus) |
| IaC | Terraform, AWS CDK |
| Delivery | Docker, Kubernetes, Helm, Argo CD, GitHub Actions, GitLab CI |
| Observability | Grafana, Prometheus, Alloy, Loki, CloudWatch, Datadog, alerting, incident response |
| Security | Trivy, Gitleaks, OIDC, Keycloak, Sealed Secrets |
| Data | PostgreSQL, Redis/Valkey, SQL migrations |

</details>

## Side projects

- **[Enterprise-k8s-platform](https://github.com/KirilMilosevski/Enterprise-k8s-platform)** — GitOps Kubernetes platform: Terraform, Argo CD, Traefik, cert-manager, observability, Cloudflare tunnel
- **[Homelab](https://github.com/KirilMilosevski/Homelab)** — Archived early lab (superseded by Enterprise-k8s-platform)

<p>
  <img src="https://img.shields.io/website?url=https%3A%2F%2Fkirilmilosevski.github.io%2Fkiril-cv-landing%2F&label=portfolio&up_message=online&style=for-the-badge" alt="Portfolio status" />
  <a href="https://github.com/KirilMilosevski/Enterprise-k8s-platform/actions/workflows/main-ci.yml"><img src="https://github.com/KirilMilosevski/Enterprise-k8s-platform/actions/workflows/main-ci.yml/badge.svg" alt="Enterprise-k8s-platform CI" /></a>
</p>

## Links

- Portfolio: [kirilmilosevski.github.io/kiril-cv-landing](https://kirilmilosevski.github.io/kiril-cv-landing/)
- LinkedIn: [kiril-milosevski](https://www.linkedin.com/in/kiril-milosevski-603b25241)
