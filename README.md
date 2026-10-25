<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000428,50:004e92,100:000428&height=280&section=header&text=Prabhat%20Ranjan&fontSize=70&fontColor=00d2ff&animation=fadeIn&fontAlignY=36&desc=Senior%20Cloud%20%26%20DevOps%20Architect%20%7C%20DevSecOps%20Specialist%20%7C%20AI%20Ops&descFontSize=20&descColor=e0f2fe&descAlignY=62" width="100%" />

<!-- Animated Dynamic Typing Banner -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=23&pause=1200&color=00F0FF&center=true&vCenter=true&multiline=true&width=850&height=90&lines=⚡+Senior+Cloud+%26+DevSecOps+Architect;☁️+Enterprise+Azure+Landing+Zones+%26+Hub-and-Spoke+Networking;🚀+100%2B+Workload+Enterprise+Migrations+Engineered;🧠+AI-Driven+DevOps+%7C+Model+Context+Protocol+(MCP)+%26+RAG;💰+FinOps+Governance+%26+Cloud+Economics+Optimization" alt="Typing SVG" />
</a>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Cloud%20Architecture%20%26%20DevSecOps-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Security-Zero--Trust%20%26%20PIM-red?style=for-the-badge&logo=shield" />
  <img src="https://img.shields.io/badge/AI%20Ops-MCP%20%26%20RAG%20Enabled-8A2BE2?style=for-the-badge&logo=openai" />
  <img src="https://img.shields.io/badge/Migration-100%2B%20Workloads-success?style=for-the-badge&logo=azure" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:devopsranjan_998877@outlook.com"><img src="https://img.shields.io/badge/Email-Get%20in%20Touch-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/prabhat952359"><img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

<!-- Animated Glowing Divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4300-a447-11eb-908a-139a6edaec5c.gif" width="100%" />

</div>

## 👨‍💻 About Me

Hello! I'm **Prabhat Ranjan**, a **Senior Cloud & DevOps Architect** and **DevSecOps Specialist** with extensive experience in designing, automating, securing, and operating enterprise cloud environments.

I specialize in building mission-critical, zero-trust cloud platforms using modern Infrastructure as Code (IaC), container orchestration, automated security guardrails, and cloud economics (FinOps). Recently, I have also been integrating **Next-Gen AI Platform Engineering** — leveraging **Model Context Protocol (MCP)** and **Retrieval-Augmented Generation (RAG)** to build autonomous telemetry and runbook intelligence into DevOps pipelines.

---

## ⚡ Architectural Competencies & Impact

<div align="center">

| ☁️ Enterprise Cloud Architecture | 🛡️ Zero-Trust DevSecOps | 🚀 100+ Cloud Migrations | 🧠 Next-Gen AI Ops |
| :---: | :---: | :---: | :---: |
| Azure Landing Zones (CAF), Hub & Spoke VNets, ExpressRoute, and Multi-Region HA. | Shift-Left gates: Checkov, Trivy, Gitleaks, Azure Policy & Microsoft Entra PIM. | 100+ workloads migrated from on-prem to cloud with zero downtime cutovers. | Custom **Model Context Protocol (MCP)** servers & **RAG** for automated incident triage. |

</div>

---

## ☁️ Enterprise Cloud Architecture & Governance

I design enterprise-ready cloud architectures aligned with the **Microsoft Cloud Adoption Framework (CAF)**:

### 🌐 1. Hub-and-Spoke Network Architecture
* **Central Connectivity:** Hub VNet housing ExpressRoute / S2S VPN Gateways, Azure Firewall / NVAs with TLS inspection, and central Private DNS Zones.
* **Controlled Traffic & Micro-Segmentation:** User-Defined Routes (UDRs `0.0.0.0/0`) forcing egress traffic through centralized firewalls, paired with Network Security Groups (NSGs) and Application Security Groups (ASGs).
* **Private Connectivity:** Private Endpoints for PaaS services (Azure SQL, Key Vault, Storage Accounts) eliminating public internet exposure.

### 🛡️ 2. Identity, Governance & Zero-Trust
* **Hierarchy:** Clean Management Group hierarchy (`Tenant Root` ➔ `Platform` [Identity, Management, Connectivity] vs `Landing Zones` [Corp, Online]).
* **Privileged Identity Management (PIM):** Enforcing Just-In-Time (JIT) role elevation with multi-stage peer approvals and audit trails.
* **Policy-as-Code:** Assigning CIS Azure Benchmark and Microsoft Cloud Security Benchmark initiatives with automated audit/deny enforcement.

### 🔄 3. High Availability & Disaster Recovery
* **Multi-Tier Resilience:** Virtual Machine Scale Sets (VMSS) across Availability Zones.
* **Storage Redundancy:** LRS, ZRS, and GRS replication models aligned with defined business **RTO** (Recovery Time Objective) and **RPO** (Recovery Point Objective) SLAs.
* **Disaster Recovery:** Azure Site Recovery (ASR) with paired-region failover testing.

---

## 🔐 Automated Shift-Left DevSecOps Pipeline

> Security is not an afterthought — every commit and pull request must pass multi-layered automated compliance gates before reaching production.

```
[ Developer Commit / PR ]
         │
         ▼
[ Stage 1: Code Validation ] ──► terraform fmt / tflint / shell verification
         │
         ▼
[ Stage 2: Security & Secrets ]
         ├── Gitleaks     ──► Automated secret & credential detection
         ├── Checkov      ──► Static IaC posture & CIS compliance check
         └── Trivy        ──► Container image CVE & dependency vulnerability scan
         │
         ▼
[ Stage 3: FinOps Budget Gate ]
         └── Infracost    ──► Pull-request cloud cost delta & budget guardrail
         │
         ▼
[ Stage 4: Immutable Execution ]
         ├── Terraform Plan with remote state locking (Azure Blob lease)
         ├── Automated drift detection against live Azure environment
         └── PIM Just-In-Time approval gate for Production
         │
         ▼
[ Stage 5: Zero-Downtime Release ] ──► Canary / Blue-Green rollout with automated rollback
```

---

## 🧠 AI-Augmented Platform Engineering (MCP & RAG)

Bridging traditional DevOps with modern AI infrastructure:

* **Model Context Protocol (MCP):**
  * Building production **MCP Servers** that interface AI agents safely with Kubernetes clusters, Azure Monitor, and CI/CD pipelines for read-only telemetry, log inspection, and fast diagnostics without credential exposure.
* **Retrieval-Augmented Generation (RAG) for SRE & Operations:**
  * Vectorizing Architecture Decision Records (ADRs) and incident post-mortem runbooks into embedding vector databases (Chroma / Pinecone) for instant contextual guidance during outages.
* **Autonomous Drift & Vulnerability Remediation:**
  * Implementing agentic workflows that ingest Trivy/Checkov security scans and draft automated remediation pull requests.

---

## 🚀 100+ Enterprise Workload Migration Lifecycle

```
┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
│  Discovery   │ ──► │  Assessment  │ ──► │  Readiness   │ ──► │   Cutover    │ ──► │  Hypercare   │
│ Inventory &  │     │ 6R Strategy, │     │ Landing Zone │     │ Zero-Downtime│     │ 24x7 War Room│
│ Dependencies │     │ TCO & Sizing │     │ & Governance │     │ DNS/DB Sync  │     │ & Telemetry  │
└──────────────┘     └──────────────┘     └──────────────┘     └──────────────┘     └──────────────┘
```

* **10 Non-Negotiable Architectural Pillars:**  
  `1. Scalable` • `2. Robust` • `3. Secure` • `4. Reliable` • `5. Portable` • `6. Governed` • `7. High Availability` • `8. Cost-Optimized` • `9. Backed Up (RPO/RTO)` • `10. Compliant & Monitored`

---

## 💰 FinOps (Cloud Financial Management)

* **Waste Elimination:** Automated sweeps for unattached disks, orphaned IPs, obsolete snapshots, and idle compute resources.
* **Commitment Discounts:** Reserved Instances (1-year / 3-year RI) and Azure Savings Plans yielding **40-60% compute savings**.
* **Log Ingestion Tuning:** Reviewing Azure Monitor tables and creating Data Collection Rules (DCR) to filter noisy diagnostic logs, cutting log ingestion costs by **35%+**.
* **Automated Power Schedules:** Cloud functions shutting down non-production Dev/UAT environments outside business hours.

---

## 🛠️ Tech Stack & Arsenal

<div align="center">

### ☁️ Cloud & Infrastructure
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=azure,aws,gcp,linux,ubuntu,redhat" alt="Cloud" />
  </a>
</p>

### ⚙️ Containers, IaC & Orchestration
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=kubernetes,docker,terraform,ansible,bash" alt="Containers & IaC" />
  </a>
</p>

### 🔄 CI/CD & DevSecOps
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=githubactions,gitlab,jenkins,git" alt="CI/CD" />
  </a>
</p>

### 🧠 AI Platform, Backend & Monitoring
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,fastapi,prometheus,grafana,postgres,redis" alt="AI & Monitoring" />
  </a>
</p>

</div>

---

## 🏆 GitHub Achievements & Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=prabhat952359&theme=tokyonight&no-frame=true&margin-w=12&row=1&column=7" alt="GitHub Trophies" />
</div>

<br>

<div align="center">

<!-- GitHub Stats & Streak -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=prabhat952359&show_icons=true&theme=tokyonight&hide_border=true&title_color=00f0ff&icon_color=00d2ff&text_color=e0f2fe&bg_color=000428" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=prabhat952359&theme=tokyonight&hide_border=true&stroke=00f0ff&ring=00d2ff&fire=ff0055&currStreakLabel=00f0ff&background=000428" width="48%" alt="GitHub Streak" />
</p>

<!-- Top Languages Chart -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prabhat952359&layout=compact&theme=tokyonight&hide_border=true&title_color=00f0ff&text_color=e0f2fe&bg_color=000428" width="60%" alt="Top Languages" />
</p>

---

<!-- Animated Glowing Divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4300-a447-11eb-908a-139a6edaec5c.gif" width="100%" />

### 🤝 Connect With Me

*"Always excited to discuss Enterprise Cloud Transformations, DevSecOps Culture, Resilient Landing Zones, and AI-Augmented Platform Engineering."*

<br>

<a href="https://linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-Connect%20Now-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
&nbsp;&nbsp;
<a href="mailto:devopsranjan_998877@outlook.com"><img src="https://img.shields.io/badge/Email-devopsranjan__998877%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email" /></a>
&nbsp;&nbsp;
<a href="https://github.com/prabhat952359"><img src="https://img.shields.io/badge/GitHub-Follow%20Work-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

<br><br>

<!-- Animated Waving Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000428,50:004e92,100:000428&height=140&section=footer" width="100%" />

</div>
