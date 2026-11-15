<h1 align="center">Okiri Gabriel</h1>

<p align="center">
  <strong>I build the systems people trust at 3am.</strong><br>
  AI · Security · Cloud · SRE · DevOps · System architecture
</p>

<p align="center">
  Luton, England · Platform, cloud security, and DevOps engineer · Instructor<br>
  Speaker · Leader · Mentor · Solution builder
</p>

<p align="center">
  Open-source contributor across several projects.<br>
  Credited on the <a href="https://hub.xerj.org/contributors/OkiriGabriel">XERJ Corpus Hub</a>. AI coding agents pull my <a href="https://github.com/open-devops-agent/open-devops-agent">open-devops-agent</a> work as a worked example, with my name attached.
</p>

<p align="center">
  <a href="https://github.com/OkiriGabriel/">Website</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/okirigabriel/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://hub.xerj.org/contributors/OkiriGabriel">XERJ credit</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/OkiriGabriel?tab=repositories">Repositories</a>
  &nbsp;·&nbsp;
  <a href="https://x.com/OkiriGabriel">X</a>
</p>

---

### About

I sit where most engineers keep the work in separate boxes: the platform, the reliability, and the security. I design the architecture, then I ship it. Terraform, Ansible, Jenkins, GitHub Actions, Argo CD, Prometheus, Grafana, and Datadog are how that shows up. Multi-tenant Kubernetes. Security scanning as a pipeline gate, not a follow-up ticket. Identity across MFA, SSO, SAML, and OIDC.

I also work with AI infrastructure: GPU compute, containerised model serving, and MLOps pipelines, deploying and optimising ML workloads in production. At DFgates, that meant standing up Kubernetes clusters and GPU servers across AWS, GCP, Nebius AI, and RunPod, and shipping a CI/CD pipeline that improved model inference speed by 25%.

Security is built into how I design systems from day one. I've embedded SAST, DAST, SCA, and secrets scanning as mandatory pipeline gates, configured TLS/SSL and Cloudflare DDoS protection for production APIs, and implemented least-privilege IAM and Key Vault encryption across multi-tenant Azure environments. That same instinct is why I built Argus Scan, an open-source tool that unifies 20+ security scanners behind a single CLI.

I'm currently a Senior Platform Engineer at Admiral Group Plc. Outside of the day job, I write about DevOps and cloud security, speak at industry events (including SRE Day London, September 2026), mentor engineers entering the field, and build open-source tools for the SRE and platform engineering community, including DeAgent, an autonomous incident-response agent, Argus Scan, and LoopMark, a LangGraph AI marketing agent. I'm also the founder of the Luton Creative & Technology Collaboration Community, bringing cloud, DevOps, AI, and cybersecurity together with creativity and personal growth.

---

### Packages

| Package | Registry | Install |
| --- | --- | --- |
| [argus-scan](https://pypi.org/project/argus-scan/) | PyPI | `pip install argus-scan` |
| [devops-ai-agent](https://pypi.org/project/devops-ai-agent/) | PyPI | `pip install devops-ai-agent` |
| [argus-codescan](https://www.npmjs.com/package/argus-codescan) | npm | `npm install argus-codescan` |

`argus-scan` is the full security scanner: SAST, DAST, SCA, secrets, IaC, Terraform, and Ansible, from the CLI or MCP. `argus-codescan` is the Node package for React, Next.js, and Node. `devops-ai-agent` is the on-call agent for Kubernetes, cloud, and CI incidents.

---

### Selected work

**[Argus](https://github.com/argus-code-scanning/argus-codescan-mcp)** · code scanner agent  
One open-source scanner for SAST, secrets, dependencies, infrastructure, and malware heuristics. One CLI, GitHub SARIF, and an MCP server so an editor can run the scans. [Website](https://code-scan.arestechub.com/)

**[DevOps AI Agent](https://github.com/open-devops-agent/open-devops-agent)**  
An on-call agent for CI, Kubernetes, and cloud incidents. It diagnoses from real tool output, then applies a fix only after a dry-run and an approval gate.

**[Terngi AI](https://github.com/Terngi-AI/tergniai-multilang)**  
Open-source translation and conversation API for Yoruba, Hausa, Igbo, and English. FastAPI, Azure Translator, and Groq. [terngiai.com](https://www.terngiai.com)

**[Loopmark](https://github.com/loopmark-opensource/loopmark-agent)**  
Open-source marketing agent for social content, email campaigns, audience research, lead funnels, and auto-posting.

**[terraform-aws-migration](https://github.com/terraform-okirihq/terraform-aws-migration)**  
One module to move databases, file shares, servers, container images, and Kubernetes workloads from a data centre to AWS, with the CI/CD that keeps shipping them.

**[terraform-cloude-agnostic](https://github.com/terraform-okirihq/terraform-cloude-agnostic)**  
The same network, NAT, firewall, servers, and object storage on AWS, Azure, or GCP, behind one Terraform interface. Works with `terraform apply`, workspaces, HCP Terraform, and CI.

#### Few of my selected projects

**[terraform-aws-platform](https://github.com/OkiriGabriel/terraform-aws-platform)**  
One Terraform module for a secure AWS platform: profiles, ECS, RDS, Redis, VPN, guardrails, and SCP packs.

**[terraform-azure-platform](https://github.com/OkiriGabriel/terraform-azure-platform)**  
Hub-and-spoke Azure with network security, AKS, and a path for on-premises migration.

**[kubernetes-ansible-playbook-runner](https://github.com/OkiriGabriel/kubernetes-ansible-playbook-runner)**  
Run Ansible playbooks inside Kubernetes. Load the content once, then apply the runner pattern you need, without SSH keys or extra hosts.

**[argocd-terraform](https://github.com/OkiriGabriel/argocd-terraform)**  
Terraform that builds an Amazon EKS cluster and installs Argo CD with Helm, plus a small GitOps sample app.

---

### Stack

`Terraform` · `Ansible` · `Jenkins` · `GitHub Actions` · `Argo CD` · `Kubernetes` · `Prometheus` · `Grafana` · `Datadog` · `AWS` · `Azure` · `GCP` · `Python` · `MCP` · `FastAPI`

---

<p align="center">
  Building AI, security, cloud, SRE, DevOps, and system architecture. From Luton.
</p>
