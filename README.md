# Gabriel Okiri

*I build the systems people trust at 3am.*

Platform, cloud security and DevOps engineer · Instructor · Speaker · Mentor

`AI` `Security` `Cloud` `SRE` `DevOps` `System Architecture`

Open-source contributor, credited on the [XERJ Corpus Hub](https://hub.xerj.org/contributors/OkiriGabriel).

[Website](https://github.com/OkiriGabriel/) · [LinkedIn](https://www.linkedin.com/in/okirigabriel/) · [Repositories](https://github.com/OkiriGabriel?tab=repositories) · [X](https://x.com/OkiriGabriel) · [Medium](https://medium.com/@gabrielokiri)

---

## About

I design platform architecture and then build it. My work covers infrastructure as code, reliability and security, using Terraform, Ansible, Jenkins, GitHub Actions, Argo CD, Prometheus, Grafana and Datadog. I build multi-tenant Kubernetes platforms, treat security scanning as a pipeline gate rather than a follow-up ticket, and implement identity across MFA, SSO, SAML and OIDC.

I also work on AI infrastructure: GPU compute, containerised model serving and MLOps pipelines. At DFgates, I set up Kubernetes clusters and GPU servers across AWS, GCP, Nebius AI and RunPod, and delivered a CI/CD pipeline that improved model inference speed by 25%.

Security is part of the design from the start. I have made SAST, DAST, SCA and secrets scanning mandatory pipeline gates, configured TLS/SSL and Cloudflare DDoS protection for production APIs, and implemented least-privilege IAM and Key Vault encryption across multi-tenant Azure environments. The same principle led to Argus Scan, an open-source tool that unifies 20+ security scanners behind a single CLI.

My career has moved from software development to cloud engineering and DevOps in 2022, then platform engineering, then cloud security. I see these disciplines as one foundation at different depths, and I now mentor engineers entering the field.

I am a Senior Platform Engineer at Admiral Group plc. Outside work, I write about DevOps and cloud security on Medium and speak at industry events. I spoke at SRE Day London (September 2026) on *"Automate the Work, Not the Thinking: Why Disaster Recovery Comes First."* I also build open-source tools for the SRE and platform engineering community: DeAgent, an autonomous incident-response agent; Argus Scan; and LoopMark, a LangGraph AI marketing agent.

I founded the Luton Creative & Technology Collaboration Community, which brings together cloud, DevOps, AI and cybersecurity with creativity and personal growth. Its first in-person meetup, Luton Connect, ran in October 2026 and covered cloud, AWS, AI, DevOps and career transitions. I have also applied to start an official AWS User Group in Luton. [Events](https://arestechub.com/events)

## Industries

FINTECH · INSURANCE · AI · LOGISTICS · PUBLIC SECTOR · HEALTH CARE · EDTECH · ECOMMERCE

## Packages

| Package | Registry | Install |
| --- | --- | --- |
| [argus-scan](https://pypi.org/project/argus-scan/) | PyPI | `pip install argus-scan` |
| [devops-ai-agent](https://pypi.org/project/devops-ai-agent/) | PyPI | `pip install devops-ai-agent` |
| [argus-codescan](https://www.npmjs.com/package/argus-codescan) | npm | `npm install argus-codescan` |

`argus-scan` is the full security scanner covering SAST, DAST, SCA, secrets, IaC, Terraform and Ansible, available from the CLI or MCP. `argus-codescan` is the Node package for React, Next.js and Node. `devops-ai-agent` is an on-call agent for Kubernetes, cloud and CI incidents.

## Selected work

**[Argus](https://github.com/argus-code-scanning/argus-codescan-mcp)** · [Live scanner](https://code-scan.arestechub.com/)
An open-source code scanner for SAST, secrets, dependencies, infrastructure and malware heuristics, with one CLI, GitHub SARIF output and an MCP server for editor integration.

**[DevOps AI Agent](https://github.com/open-devops-agent/open-devops-agent)**
An on-call agent for CI, Kubernetes and cloud incidents. It diagnoses from real tool output and applies fixes only after a dry run and an approval gate.

**[Loopmark](https://github.com/loopmark-opensource/loopmark-agent)** · [Live demo](https://main.d3b5sf354a54dh.amplifyapp.com)
An open-source marketing agent for social content, email campaigns, audience research, lead funnels and auto-posting.

**[Terngi AI](https://github.com/Terngi-AI/tergniai-multilang)** · [terngiai.com](https://www.terngiai.com)
An open-source translation and conversation API for Yoruba, Hausa, Igbo and English, built with FastAPI, Azure Translator and Groq.

**Self-hosted Plane.io on AWS**
Project management on EC2 with RDS PostgreSQL, S3 file storage, Redis for Celery, and a Docker Compose stack.

**AWS load balancer consolidation**
A multi-wave programme to reduce load balancers across environments, with changes planned to have no routing impact.

**[terraform-aws-migration](https://github.com/terraform-okirihq/terraform-aws-migration)**
One module to move databases, file shares, servers, container images and Kubernetes workloads from a data centre to AWS, plus the CI/CD to keep shipping them.

**[terraform-cloude-agnostic](https://github.com/terraform-okirihq/terraform-cloude-agnostic)**
The same network, NAT, firewall, server and object storage stack on AWS, Azure or GCP, behind one Terraform interface that works with `terraform apply`, workspaces, HCP Terraform and CI.

### More projects

- **[terraform-aws-platform](https://github.com/OkiriGabriel/terraform-aws-platform)**: one Terraform module for a secure AWS platform, covering profiles, ECS, RDS, Redis, VPN, guardrails and SCP packs.
- **[terraform-azure-platform](https://github.com/OkiriGabriel/terraform-azure-platform)**: hub-and-spoke Azure with network security, AKS and a path for on-premises migration.
- **[kubernetes-ansible-playbook-runner](https://github.com/OkiriGabriel/kubernetes-ansible-playbook-runner)**: runs Ansible playbooks inside Kubernetes, without SSH keys or extra hosts.
- **[argocd-terraform](https://github.com/OkiriGabriel/argocd-terraform)**: Terraform that builds an Amazon EKS cluster, installs Argo CD with Helm and includes a small GitOps sample app.

## Stack

`Terraform` `Ansible` `Jenkins` `GitHub Actions` `Argo CD` `Kubernetes` `Prometheus` `Grafana` `Datadog` `AWS` `Azure` `GCP` `Python` `MCP` `FastAPI`

---

<p align="center">
  Building AI, security, cloud, SRE, DevOps and system architecture. From Luton.
</p>
