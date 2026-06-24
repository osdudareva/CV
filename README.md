# Olga Dudareva

## Senior DevOps / Platform Engineer

Barcelona, Spain · osdudareva@gmail.com · linkedin.com/in/olga-dudareva

### PROFESSIONAL SUMMARY

Senior DevOps/Platform Engineer with 8+ years of hands-on experience designing and operating cloud-
native platforms at scale. Deep expertise across the full DevOps lifecycle: GitOps delivery with GitHub
Actions and pull-request-driven automation, infrastructure-as-code with Terraform, Kubernetes orchestration
with Helm and Istio service mesh, edge security with Cloudflare, comprehensive observability
(Prometheus/Grafana stack), policy-as-code, secrets management, and end-to-end CI/CD with rigorous
release management. Experienced in Platform Engineering and Developer Experience practices - building
golden-path CI/CD workflows, reusable Helm and Terraform libraries. Strong container security background
covering image scanning, supply-chain integrity (Cosign/SBOM), and admission control (OPA Gatekeeper).
Proven ability to reduce configuration drift, enforce least-privilege security postures, and turn complex multi-
cloud environments into reliable platforms.

### CORECOMPETENCIES

**GitOps & Kubernetes:** GitHub · GitHub Actions · GitOps delivery patterns · Argo CD · Kubernetes · AKS ·
DOKS · Helm · Kustomize · custom CRDs · Istio service mesh · Calico network policies · AGIC / Application
Gateway Ingress

**Infrastructure as Code:** Terraform · Bicep · ARM Templates · Pulumi · Azure · DigitalOcean

**CI/CD & Release Management:** Azure DevOps Pipelines · GitLab CI/CD · GitHub Actions · quality gates ·
environment promotion · deployment approvals · change-control automation · release notifications · GitLab
Flow / trunk-based development

**Security & DevSecOps:** HashiCorp Vault · Azure Key Vault · OPA policy-as-code · OPA Gatekeeper · Trivy
· Cosign · SBOM generation · RBAC · OIDC/SAML · Keycloak + Entra ID federation ·
Snyk/SonarCloud/Intruder· vulnerability scanning · Intune / Conditional Access

**Platform Engineering & DevEx:** Golden-path CI/CD templates · GitOps delivery patterns · observability
foundations

**Monitoring & Observability:** Prometheus · Grafana · Loki · Mimir · Tempo · Pyroscope · Alloy · Microsoft
Sentinel · Graylog · Zabbix

**Cloudflare:** DNS · CDN· WAF · Workers · Pages · R2 · Zero Trust / Access · DDoS protection

**Database & Integration:** PostgreSQL (HA clusters · Atlas schema migrations) · Azure SQL · Cosmos DB ·
Valkey · Azure Service Bus · Azure Data Factory · Data Lake Gen2 · Azure AI Search

**Automation & Scripting:** Ansible · Bash · PowerShell · Python · TypeScript

### PROFESSIONAL EXPERIENCE

### Homerun Management AG · Senior DevOps Engineer Jun 2024 – Present | Barcelona, Spain

_Lead platform engineering for a multi-region, multi-tenant e-commerce & licensing platform running on Azure
AKS and DigitalOcean Kubernetes._

```
▪ GitOps & Delivery Automation : Designed and operated end-to-end GitOps delivery workflows using
GitHub as the source of truth - branch protection rules, environment-scoped deployment policies,
reusable GitHub Actions workflows, and automated promotion gates across dev/staging/production;
enforced pull-request-driven change control with automated status checks, approvals, and audit trails.
▪ Kubernetes & Helm : Managed full Kubernetes cluster lifecycle on AKS and DigitalOcean - node pool
configuration, upgrades, RBAC, resource quotas, and network policies; authored and maintained
reusable Helm chart libraries for multi-tenant workloads and wrote Kustomize overlays for environment-
specific configuration; developed custom CRDs to extend Kubernetes APIs for internal platform tooling.
▪ Terraform IaC : Owned end-to-end Terraform estate across Azure and DigitalOcean - designing and
managing the majority of cloud resources (AKS/DOKS clusters, VNets, private networking, DNS,
storage, databases, IAM, ingress); built a standardised Terraform module library with remote state
locking and workspace-per-environment strategy, eliminating manual provisioning and configuration drift
across all environments.
▪ Istio & Zero-Trust Networking : Deployed and operated Istio service mesh to secure inter-service
communication with mTLS enforcement; integrated with OPA policies to control traffic and enforce fine-
grained access rules at the service level; used Istio alongside Calico network policies.
▪ Cloudflare : Managed the full Cloudflare platform stack - CDN cache rules, WAF rulesets, Workers,
Pages, DNS zone management, R2 object storage.
▪ CI/CD & Release Management : Built Azure DevOps pipeline templates with quality gates (SonarCloud,
Snyk dependency scan, Intruder), OPA policy checks, environment promotion approvals; standardised
branching strategy and change-control automation.
▪ Security & Secrets Management : Implemented HashiCorp Vault dynamic secrets, Azure Key Vault
CSI driver integration; enforced RBAC, workload identity (OIDC), and audit logging across all secret
access paths.
▪ Identity & Access Management : Deployed self-hosted Keycloak federated with Azure Entra ID and
B2C tenants; configured OIDC/SAML flows, RBAC roles, MFA enforcement, Intune Conditional Access
policies, and risk-based access controls.
▪ Monitoring & Observability : Built full-stack observability with Prometheus, Grafana (Loki logs, Mimir
metrics long-term storage, Tempo traces, Pyroscope profiling, Alloy collector); created SLO dashboards,
and automated Sentinel detections with Logic Apps response playbooks.
▪ Container Security & Supply Chain : Integrated Trivy image scanning into CI pipelines; implemented
Cosign container signing and verification, and SBOM generation to enforce a full software supply-chain
security posture.
▪ Platform Engineering & Developer Experience : Established golden-path CI/CD templates, reusable
Helm chart library.
▪ Database & Platform Services : Managed HA PostgreSQL clusters with Atlas schema migration
pipeline; integrated Temporal workflows (TypeScript), Airflow DAGs (Python) event flows into release
and operational processes.
```
### EPAM Systems · Senior DevOps Engineer Nov 2020 – Jun 2024 | Remote

_Delivered DevOps and platform engineering services across multiple enterprise Azure client engagements._

```
▪ Terraform & IaC Standardisation : Led migration from legacy ARM Templates to Terraform + Bicep
across multi-environment Azure estates; built a reusable module library and enforced naming
conventions, tagging standards, and remote state management.
▪ CI/CD & Release Practices: Designed and maintained Azure DevOps, GitHub Actions, and GitLab
CI/CD pipelines with automated testing, SonarQube quality gates, environment-specific approvals,
deployment notifications, artifact promotion, and rollback-aware release patterns.
▪ Kubernetes & Helm Delivery: Supported Kubernetes-based application delivery for enterprise client
environments, packaging services with Helm, maintaining environment-specific deployment manifests,
troubleshooting pods, networking, resource limits, and deployment failures, and integrating Kubernetes
releases into CI/CD promotion flows.
▪ Azure Data Platform : Integrated Azure Data Factory pipelines with Data Lake Gen2, Azure SQL,
Cosmos DB, and on-premises Oracle; enabled repeatable multi-environment data workflow delivery with
parameterised pipeline templates.
▪ Operations Automation : Authored PowerShell/Bash runbooks for VM patching, scheduled start/stop,
cost reporting, and incident remediation via Azure Automation; reduced toil and improved operational
visibility across multiple tenants.
▪ Cross-Functional Collaboration : Partnered with QA and application teams to shift testing left by
integrating unit, integration, and smoke tests into pipelines, reducing manual coordination and post-
deployment defects.
▪ Mentoring & Knowledge Sharing : Mentored junior and mid-level DevOps engineers on IaC patterns,
pipeline design, and Azure platform practices; ran internal tech-talks and created onboarding guides to
accelerate team ramp-up across client engagements.
```
### Digital Design · Systems Engineer (DevOps) Junior → Middle → Senior Nov 2017 – Nov 2020

St. Petersburg, Russia

_Progressed through three levels delivering CI/CD, monitoring, and infrastructure automation for on-premises
and hybrid microservices environments._

```
▪ CI/CD : Built GitLab CI/CD and TeamCity pipelines with automated deployments, merge-request
automation, and multi-environment promotion; standardised branching and review workflows across
engineering teams.
▪ Monitoring Stack : Designed and deployed Prometheus/Grafana/Graylog/Zabbix observability bundle
packaged as Docker Compose; enabled rapid rollout of standardised monitoring to new customer
environments.
▪ Configuration Management : Automated on-premises Linux (Ubuntu/CentOS) and Windows Server
configuration with Ansible playbooks covering OS hardening, application deployment, backup, and DR
procedures.
▪ Security : Implemented secure Nginx web server configurations with GOST/RSA encryption and
CryptoPro CA; authored SSH tunnel management automation and security hardening scripts.
▪ Mentoring : As Senior, mentored junior team members on CI/CD pipeline design, Linux administration,
and scripting best practices; contributed to internal knowledge base and code review culture.
```
### CERTIFICATIONS

```
▪ AZ-400: Designing and Implementing Microsoft DevOps Solutions — Microsoft
▪ AZ-104: Microsoft Azure Administrator — Microsoft
```
### EDUCATION

**B.S. Information Systems and Technologies** · Saint Petersburg Mining University · 2015 – 2019

### L A N G U A G E S

**English** — Professional working proficiency · **Russian** — Native / bilingual


