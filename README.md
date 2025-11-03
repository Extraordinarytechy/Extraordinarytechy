# Hi, I'm Ajay Kumar  

I am a Cloud & DevOps Engineer with a passion for building, automating and managing scalable, high-availability infrastructure. I believe in a "T-shaped" engineering approach: deep expertise in modern cloud-native systems, combined with a broad understanding of traditional IT operations.

To demonstrate these skills, I have built a complete, four-part SDE portfolio. This isn't just a collection of random projects; it's a single, interconnected ecosystem.

---

## My "T-Shaped" SDE Portfolio

This portfolio is built around a "Flagship + Satellites" model. The **Flagship** project is a deep, complex, cloud-native platform, while the **Satellites** are professional-grade projects that solve critical, real-world operational problems (Cost, Reliability, and Legacy Systems).

This strategy mirrors a real enterprise environment, which consists of both modern (EKS) and traditional (EC2) infrastructure.

```

\+-------------------------------------------------------------+
|               PROJECT 1: THE FLAGSHIP                        |
|           [Internal Developer Platform (IDP) on EKS]         |
\+----------------------+-------------------+------------------+
|                       |                   |
|                       |                   |     
\+----------------------+                   |
|  PROJECT 2: SATELLITE |                   |
|  [FinOps Guardian]    |                   |
|  (Manages Cost)       |                   |
\+----------------------+                   |
|                                           | 
\+-------------------+----------------------+
|                                           |
\+----------------------+                   +-----------------------------+
|  PROJECT 3: SATELLITE  |                  |  PROJECT 4: SATELLITE       |
|  [Observability Hub]   |                  |  [Ansible Fleet Automation] |
|  (Manages Reliability) |                  |  (Manages Legacy Systems)   |
\+----------------------+                   +-----------------------------+

```

### The 4 Projects

This is the central hub for accessing all four projects.

| Project | Repository | Core Competency | Key Technologies |
| :--- | :--- | :--- | :--- |
| 1. **IDP Flagship** | [`idp-flagship-iac`](https://github.com/Extraordinarytechy/idp-flagship-iac) | Cloud-Native IaC & CI/CD | `Terraform`, `AWS EKS`, `ArgoCD`, `GitHub Actions` |
| 2. **FinOps Guardian** | [`aws-finops-guardian`](https://github.com/ExtraordinaryTechy/finops-guardian) | Cloud Governance & Serverless | `AWS Lambda`, `Boto3`, `Cost Explorer`, `EventBridge` |
| 3. **Observability Hub** | [`k8s-observability-stack`](https://github.com/Extraordinarytechy/k8s-observability-stack) | SRE & Monitoring | `Prometheus`, `Grafana`, `Helm`, `Alertmanager` |
| 4. **Ansible Fleet** | [`ansible-fleet-automation`](https://github.com/Extraordinarytechy/ansible-fleet-automation) | Config Management & HA | `Ansible`, `ALB`, `Auto Scaling Groups`, `Terraform` |

---

## Portfolio Highlights & Technical Deep Dives

These projects are built on the real-world debugging and engineering solutions required in production environments. Below are some of the key technical challenges I successfully solved during their development.

* **Project 3 (Observability):** Debugged a "silent" Helm deployment failure. Traced the root cause from a `RECONCILED False` state on the `Alertmanager` CRD all the way back to an `undefined receiver "null"` error in the operator's log, which was caused by invisible YAML-corrupting characters.

* **Project 3 (Observability):** Engineered a two-file, production-safe deployment for Alertmanager, manually injecting the configuration via a `kubectl create secret` command to bypass Helm's file parsing and successfully launch the pod.

* **Project 1 (IDP Flagship):** Resolved persistent `FailedScheduling` errors on EKS pods that required storage. The fix involved provisioning the `aws-ebs-csi-driver` as a Terraform-managed `aws_eks_addon`, complete with a custom IAM Role (IRSA) for the service account.

* **Project 4 (Ansible Fleet):** Demonstrated a "self-healing" infrastructure by analyzing a "failed" playbook. Proved that the failure was *correct* behavior, as the Auto Scaling Group had terminated an unhealthy instance, and my Dynamic Inventory script had correctly found the *new, unconfigured* server.

* **Project 4 (Ansible Fleet):** Architected the project to demonstrate "Day 2" operational tasks (e.g., `playbook-rolling-restart.yml`) on mutable infrastructure, and can articulate the critical trade-offs vs. a "Golden AMI" (immutable) pipeline.

---

## Let's Connect

Thank you for visiting. I am always open to discussing technology and new opportunities.

* **Email:** `extraordinarytechy@gmail.com`
```
