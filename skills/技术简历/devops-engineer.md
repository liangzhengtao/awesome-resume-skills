# DevOps/SRE Resume Skill

> Resume for DevOps engineers, SREs, platform engineers, and cloud architects.

## When to Use

- Applying to DevOps Engineer, SRE, Platform Engineer, Cloud Architect roles
- Infrastructure-focused positions at any company size
- When the posting mentions CI/CD, Kubernetes, AWS/GCP/Azure, or IaC
- Consulting roles focused on cloud migration or infrastructure

## Framework

### DevOps Resume Structure

1. **Header** — Name, email, LinkedIn, GitHub, certifications badge line
2. **Summary** — Years + specialization + scale of infrastructure managed
3. **Certifications** — AWS/GCP/Azure certs, CKA, Terraform, etc.
4. **Technical Skills** — Grouped by category
5. **Experience** — Uptime, cost savings, automation metrics
6. **Education**

### Skills Section

```
TECHNICAL SKILLS
Cloud:           AWS (EC2, EKS, Lambda, RDS, S3, CloudFront),
                 GCP (GKE, Cloud Run, BigQuery), Azure (AKS)
IaC:             Terraform, Pulumi, CloudFormation, Ansible, Chef
Containers:      Docker, Kubernetes, Helm, Kustomize, Istio
CI/CD:           GitHub Actions, GitLab CI, Jenkins, ArgoCD, Flux
Monitoring:      Prometheus, Grafana, Datadog, PagerDuty, ELK Stack
Languages:       Python, Bash, Go, YAML, HCL
Networking:      VPC, DNS, Load Balancers, CDN, Service Mesh
Security:        Vault, AWS IAM, RBAC, SOC2, OWASP
Databases:       PostgreSQL, MySQL, Redis, DynamoDB, MongoDB
```

### Quantifying Reliability Improvements

```
FORMULA:
[Action] + [Scale] + [Before Metric] → [After Metric] + [Business Impact]

EXAMPLES:
• Reduced deployment time from 4 hours to 8 minutes by implementing
  GitOps with ArgoCD across 47 microservices, enabling 15+ daily
  releases (previously bi-weekly)

• Achieved 99.99% uptime (52 minutes downtime/year) for payment
  processing system handling $50M+ monthly transactions through
  multi-AZ architecture and automated failover

• Cut infrastructure costs by $180K/year (35% reduction) by
  implementing auto-scaling, right-sizing EC2 instances, and
  migrating to Graviton processors
```

## Templates

### DevOps Engineer Template

```
[FULL NAME]
[Email] | [LinkedIn] | [GitHub]

CERTIFICATIONS
[AWS Solutions Architect Professional] | [CKA] | [Terraform Associate]
[GCP Professional Cloud Architect] | [AWS Security Specialty]

SUMMARY
DevOps engineer with [X] years automating infrastructure and CI/CD
pipelines. Managed [scale — number of services, servers, clusters]
across [cloud providers]. Reduced deployment time by [X]% while
maintaining [X]% uptime.

TECHNICAL SKILLS
[Formatted skills section as shown above]

EXPERIENCE

[Company] — DevOps Engineer / SRE                    [MM/YYYY] – Present

Infrastructure & Automation:
• Designed and managed Kubernetes clusters (EKS/GKE) running [X]
  microservices with [X] pods, achieving 99.95% uptime SLA.
• Built Terraform modules for [scope], reducing infrastructure
  provisioning time from [X] days to [Y] minutes and eliminating
  configuration drift across [X] environments.
• Implemented GitOps deployment pipeline using ArgoCD, enabling
  [X] daily deployments with automated rollback on failure.

Reliability & Monitoring:
• Designed observability stack (Prometheus + Grafana + PagerDuty)
  monitoring [X]K metrics across [X] services, reducing MTTR from
  [X] hours to [Y] minutes.
• Led incident response for [X] P1/P2 incidents, maintaining [X]%
  SLA compliance. Created runbooks reducing resolution time by [X]%.
• Conducted [X] chaos engineering experiments, identifying and fixing
  [Y] single points of failure before they caused outages.

Cost & Security:
• Reduced cloud spend by $[X]K/year ([X]%) through reserved instances,
  spot fleets, and right-sizing recommendations.
• Implemented zero-trust networking with [tool], achieving SOC2
  Type II compliance and passing [X] security audits.

[Previous Company] — Junior DevOps Engineer         [MM/YYYY] – [MM/YYYY]
• [Achievement with metrics]
• [Achievement with metrics]

EDUCATION
[Degree] in [CS/IT/related] — [University] — [Year]
```

### SRE Template

```
[FULL NAME]
[Email] | [LinkedIn] | [GitHub]

CERTIFICATIONS
[CKA] | [AWS Solutions Architect Pro] | [Google SRE Books Reader :)]
[GCP Professional DevOps Engineer]

SUMMARY
Site Reliability Engineer with [X] years ensuring [scale] systems
meet their SLOs. Expertise in [observability/automation/incident
management]. Committed to reducing toil and improving developer
productivity.

TECHNICAL SKILLS
SLO/SLI:         [SLO framework, error budgets, SLI design]
Monitoring:      Prometheus, Grafana, Datadog, New Relic, PagerDuty
IaC:             Terraform, Pulumi, CloudFormation
Containers:      Kubernetes, Docker, Helm, Istio, Envoy
CI/CD:           [Tools]
Languages:       Python, Go, Bash
Databases:       [Managed services and self-hosted]
Chaos:           Chaos Monkey, Litmus, Gremlin

EXPERIENCE

[Company] — Site Reliability Engineer               [MM/YYYY] – Present

Reliability:
• Defined and maintained SLOs for [X] critical services (99.9%–99.99%
  availability), tracking error budgets and driving reliability
  improvements when budgets were at risk.
• Reduced P1 incident frequency from [X]/month to [Y]/month through
  proactive monitoring, runbook automation, and architectural hardening.
• Achieved [X]% reduction in MTTR by implementing automated incident
  response: auto-scaling triggers, self-healing pods, and intelligent
  alerting with [tool].

Toil Reduction:
• Automated [X]% of operational toil (previously [X] hours/week)
  through scripts, runbooks, and self-service tooling.
• Built self-service platform enabling [X] development teams to
  provision infrastructure in [Y] minutes (previously [X] days
  via tickets).
• Designed and implemented capacity planning model, forecasting
  resource needs [X] months ahead with [X]% accuracy.

Incident Management:
• Led incident response for [X]+ incidents, maintaining [X]% SLA
  compliance across [Y] services.
• Created incident postmortem culture, producing [X] postmortems
  with [Y] action items tracked to completion.
• Conducted [X] game days / chaos engineering experiments.

EDUCATION
[Degree] — [University] — [Year]
```

### Cloud Architect Template

```
[FULL NAME]
[Email] | [LinkedIn]

CERTIFICATIONS
[AWS Solutions Architect Professional] | [GCP Professional Cloud Architect]
[Azure Solutions Architect Expert] | [CKA] | [Terraform Associate]

SUMMARY
Cloud architect with [X] years designing and implementing cloud-native
architectures. Led cloud migrations for [X] organizations, managing
$[X]M+ in annual cloud spend. Expert in multi-cloud and hybrid strategies.

EXPERIENCE

[Company] — Cloud Architect / Principal Engineer    [MM/YYYY] – Present

Architecture & Design:
• Designed multi-region active-active architecture for [system],
  achieving 99.99% availability and RPO/RTO of <1 minute for
  [business critical application].
• Led migration of [X] applications from [source] to [cloud],
  completing [X] months ahead of schedule with zero data loss.
• Architected serverless data platform processing [X]TB/day,
  reducing compute costs by [X]% vs. previous VM-based solution.

Cloud Strategy:
• Developed cloud governance framework adopted by [X] teams,
  including tagging policies, cost allocation, and security baselines.
• Designed multi-cloud strategy for [company], distributing workloads
  across [AWS/GCP/Azure] for [resilience/compliance/cost] optimization.
• Created cloud cost optimization program saving $[X]K/year through
  reserved capacity planning, rightsizing, and waste elimination.

Team & Process:
• Mentored [X] engineers on cloud-native best practices.
• Established Architecture Review Board, evaluating [X] design
  proposals per quarter.
• Created internal cloud training program adopted by [X] teams.

EDUCATION
[Degree] — [University] — [Year]
```

## Examples

### Before & After: Infrastructure Achievement

**Before:**
```
- Managed AWS infrastructure
- Set up CI/CD pipeline
- Handled deployments
```

**After:**
```
• Managed AWS infrastructure across 3 accounts (150+ EC2 instances,
  12 EKS clusters, 50+ RDS databases) with 99.97% uptime, serving
  5M+ daily active users.

• Built CI/CD pipeline (GitHub Actions → ArgoCD → EKS) reducing
  deployment time from 4 hours to 8 minutes, enabling 15+ daily
  releases with automated canary analysis and rollback.

• Implemented blue-green deployment strategy for zero-downtime
  releases, eliminating the [X]-minute maintenance windows that
  previously impacted [X]K users monthly.
```

### Cost Optimization Metrics

```
QUANTIFYING COST SAVINGS:

• Reserved Instance strategy: $XX,XXX/year savings (X% of compute)
• Spot Fleet for batch workloads: $XX,XXX/year savings (X% reduction)
• Right-sizing recommendations: $XX,XXX/year savings (X instances)
• Storage tiering (S3 Intelligent-Tiering): $X,XXX/year savings
• Data transfer optimization: $X,XXX/year savings

TOTAL: $XXX,XXX/year (X% overall reduction)
```

## Common Mistakes

1. **Listing tools without context** — "Kubernetes" means nothing without scale
2. **No uptime/reliability metrics** — Always include SLA compliance numbers
3. **Missing cost optimization** — Companies care about cloud spend
4. **Not mentioning scale** — How many servers? How much traffic? What budget?
5. **Ignoring security** — Compliance, audits, and security posture matter
6. **No mention of incident response** — Show you can handle outages
7. **Forgetting developer experience** — DevOps is about enabling developers

---

## 中文版本

### 适用场景

- 申请DevOps工程师、SRE、平台工程师、云架构师岗位
- 云迁移或基础设施咨询角色
- 职位描述涉及CI/CD、Kubernetes、云平台

### 中文DevOps简历要点

- **认证**：AWS/GCP/Azure认证在国内含金量很高
- **量化指标**：可用性（99.99%）、部署频率、MTTR、成本节省
- **规模描述**：集群数、服务数、QPS、数据量
- **安全合规**：等保、ISO27001等国内合规要求

### 国内DevOps技术栈特点

- 阿里云/腾讯云/华为云经验更受重视
- Jenkins仍然是主流CI/CD工具
- K8s在国内普及率很高
- 运维自动化和监控体系建设经验很重要
