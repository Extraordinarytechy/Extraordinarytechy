# Ajay Kumar

### Cloud & DevOps Engineer

I build and operate cloud systems on AWS and Kubernetes. My work centers on Infrastructure as Code,
containers and GitOps, reliability and observability, and keeping AI-assisted tooling grounded and safe to
run in production.

AWS Community Builder (Cloud Operations) and Google Certified Associate Cloud Engineer.

---

## Featured Projects

| Project | Links | Overview |
|:--------|:------|:---------|
| **DriftMind** | [live](https://d1wyryu1twvwy.cloudfront.net/) · [repo](https://github.com/Extraordinarytechy/driftmind) · [article](https://builder.aws.com/content/3GmFtvchWqUUzp0UP7NXyrp5KKb/weekend-agent-challenge-driftmind-an-autonomous-ai-infrastructure-drift-detection-agent) | Detects AWS infrastructure drift: snapshots resources, computes a deterministic diff, then sends only that evidence to Amazon Bedrock under a strict JSON contract to explain the change. Emails a summary via SES. Deployed on CloudFront. |
| **RemedyAI** | [live](https://d1fnfajqesgvsl.cloudfront.net/) · [repo](https://github.com/Extraordinarytechy/remedy-ai) | Serverless app that checks a faulty product against official warranty, free-repair, card-benefit and consumer-law sources through a deterministic eligibility engine, then prepares the claim. Textract and Bedrock read receipts and photos only; they never decide coverage. 337 tests. |
| **OpsMind** | [repo](https://github.com/Extraordinarytechy/opsmind) | Kubernetes incident-response helper: on an SLO alert it gathers evidence, asks a diagnosis provider (deterministic or Bedrock) under a strict contract, then proposes gated remediations that are dry-run by default. 14 unit tests and CI. |
| **Internal Developer Platform** | [repo](https://github.com/Extraordinarytechy/idp-flagship-iac) | Platform on Amazon EKS: multi-AZ Terraform (VPC, EKS with IRSA, RDS, ECR), images pushed to ECR via keyless GitHub Actions OIDC, and ArgoCD syncing Kustomize across dev and prod. |
| **Kubernetes Observability Stack** | [repo](https://github.com/Extraordinarytechy/k8s-observability-stack) | Kubernetes monitoring with Prometheus, Grafana, Alertmanager and SRE alert rules, deployed via Helm. |
| **S3 Vectors Pre-filtering Benchmark** | [repo](https://github.com/Extraordinarytechy/s3vectors-prefilter-bench) · [writeup](https://dev.to/aws-builders/i-tested-amazon-s3-vectors-new-pre-filtering-against-exact-ground-truth-42f8) | Reproducible benchmark of Amazon S3 Vectors metadata pre-filtering: 50,000 vectors and roughly 6,900 queries scored against exact nearest neighbours, including negative results. |

Additional repositories cover FinOps cost reporting and tag governance, Ansible fleet automation, and
serverless pipelines.

---

## Open Source

- **Argo Workflows (CNCF)** — submitted a UI pull request adding pagination to the Cluster Workflow Templates
  page ([#17189](https://github.com/argoproj/argo-workflows/pull/17189)), currently under maintainer review.

---

## Writing

I write about cloud operations and AWS, mostly on dev.to and AWS Builder.

- [I Tested Amazon S3 Vectors' New Pre-Filtering Against Exact Ground Truth](https://dev.to/aws-builders/i-tested-amazon-s3-vectors-new-pre-filtering-against-exact-ground-truth-42f8) — a measured benchmark, including where it falls short.
- [The Most Important AWS AI Announcement Wasn't a Model. It Was an Operating Model](https://dev.to/aws-builders/the-most-important-aws-ai-announcement-wasnt-a-model-it-was-an-operating-model-39dk) — on Amazon Bedrock AgentCore and operating agents at scale.
- [DriftMind: an infrastructure drift-detection agent](https://builder.aws.com/content/3GmFtvchWqUUzp0UP7NXyrp5KKb/weekend-agent-challenge-driftmind-an-autonomous-ai-infrastructure-drift-detection-agent) — on AWS Builder.

More at [dev.to/extraordinarytechy](https://dev.to/extraordinarytechy).

---

## Technology Stack

| Domain | Technologies |
|:-------|:-------------|
| **Cloud** | AWS (EC2, S3, VPC, EKS, Lambda, API Gateway, DynamoDB, RDS, ECR, CloudFront, CloudWatch, SNS, SES, IAM, Bedrock, Textract), Google Cloud (Cloud Run, Cloud Build) |
| **Infrastructure & Platform** | Terraform, Kubernetes (Amazon EKS), Docker, Helm, Kustomize, ArgoCD, Ansible |
| **CI/CD & Automation** | GitHub Actions, Jenkins, Python (FastAPI), Bash, Git |
| **Reliability & Observability** | SLIs/SLOs, error budgets, Prometheus, Grafana, CloudWatch, Linux, TCP/IP, DNS, SSL/TLS |

---

## Certifications & Recognition

| | Details |
|:--|:--|
| **AWS Community Builder** | Cloud Operations, 2026 cohort |
| **Google Associate Cloud Engineer** | Deploying, operating and monitoring workloads on Google Cloud |

---

## Contact

- Email: extraordinarytechy@gmail.com
- LinkedIn: [linkedin.com/in/extraordinarytechy](https://linkedin.com/in/extraordinarytechy)
- dev.to: [dev.to/extraordinarytechy](https://dev.to/extraordinarytechy)
