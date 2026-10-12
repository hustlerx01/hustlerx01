<p align="center">
  <img src="assets/banner.svg" alt="root@hustlerx:~# whoami — Ansar Shaikh // SOC · Cloud Security · Detection Engineering" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2800&pause=900&color=00372f&center=true&vCenter=true&width=520&lines=SOC+Analyst+in+the+making;Detection+Engineering;Cloud+%26+DevSecOps;AI+%2F+LLM+Security;CTF+Player+%E2%80%94+HTB+%C2%B7+THM" alt="SOC Analyst in the making · Detection Engineering · Cloud & DevSecOps · AI / LLM Security · CTF Player — HTB · THM" />
</p>

```bash
ansar@hustlerx:~$ cat about.txt
name      : Ansar Shaikh
location  : Pune, India
education : B.E. Information Technology (2025), Honours in Cybersecurity
focus     : SOC · detection engineering · cloud security · AI security
certs     : CEH Practical (EC-Council)
ctf       : CloudSEK CTF 2025, 13th place
now       : hunting boxes on Hack The Box & TryHackMe
```

**What I focus on**
- **SOC & detection engineering** — SIEM/IDS labs, Sigma rules as code, log triage, phishing analysis, threat intel
- **Cloud security & DevSecOps** — hardened AWS with Terraform, CSPM checks, policy-as-code, supply-chain signing
- **AI security** — prompt-injection testing and defenses for LLM/RAG apps, output redaction, MCP auditing
- **DevOps / SRE** — SLO alerting, monitoring, log pipelines, GitOps and safe deployments

Open to **SOC / security analyst, cloud security, DevSecOps / SRE and AI security** roles.

## 🚀 Featured projects


### 🛡️ SOC & Detection Engineering

| Project | What it does |
|---|---|
| [siem-lab](https://github.com/hustlerx01/siem-lab) | Wazuh SIEM and Suricata IDS detection lab with custom rules and tests |
| [detection-rules-as-code](https://github.com/hustlerx01/detection-rules-as-code) | Sigma detection rules with CI linting, pySigma conversion to Splunk and TP/FP replay tests |
| [evtx-triage](https://github.com/hustlerx01/evtx-triage) | Windows event log (EVTX) triage with ATT&CK-mapped rules on public attack samples |
| [pcap-hunter](https://github.com/hustlerx01/pcap-hunter) | PCAP to Zeek-style logs to Suricata-style alerts to an incident ticket |
| [soc-honeypot-lab](https://github.com/hustlerx01/soc-honeypot-lab) | Honeypot log lab with Sentinel-style detections that run locally |
| [phishdesk-in](https://github.com/hustlerx01/phishdesk-in) | Explainable .eml phishing analyser with Indian bank/UPI lure rules |
| [soar-mini](https://github.com/hustlerx01/soar-mini) | Small SOAR playbook: IOC enrichment with VirusTotal, AbuseIPDB and URLhaus, scoring and human approval for destructive actions |
| [ioc-aggregator](https://github.com/hustlerx01/ioc-aggregator) | Pulls public threat-intel feeds, normalises and de-duplicates IOCs and exports STIX 2.1 |
| [ssh-threat-feed](https://github.com/hustlerx01/ssh-threat-feed) | SSH honeypot and auth.log parser that builds a scored threat feed (txt, CSV, JSON, STIX 2.1) |
| [SSH-Log-Alert](https://github.com/hustlerx01/SSH-Log-Alert) | Bash script that emails a Mailgun alert on successful SSH logins from IPs or countries outside an allowlist |

### ☁️ Cloud Security & DevSecOps

| Project | What it does |
|---|---|
| [hardened-aws-web-tier](https://github.com/hustlerx01/hardened-aws-web-tier) | Terraform for a hardened AWS web tier: private EC2 behind an ALB, IMDSv2, SSM instead of SSH, CloudTrail, GuardDuty, KMS and GitHub OIDC. Static checks only, not applied |
| [mini-cspm-aws](https://github.com/hustlerx01/mini-cspm-aws) | 20 CIS AWS Foundations checks in boto3, tested against a moto-mocked account |
| [iac-scan-bench](https://github.com/hustlerx01/iac-scan-bench) | Benchmark of Checkov vs tfsec vs custom Rego on Terraform with planted misconfigurations |
| [k8s-policy-pack](https://github.com/hustlerx01/k8s-policy-pack) | Six Pod Security controls written in both Kyverno and OPA/Rego, with a parity test |
| [signed-by-default](https://github.com/hustlerx01/signed-by-default) | Supply-chain pipeline: cosign keyless signing, SBOM attestation, SLSA provenance and Kyverno admission |
| [vulnops](https://github.com/hustlerx01/vulnops) | Merges Trivy, Grype and ZAP findings into one risk-ranked fix queue using CVSS, EPSS and CISA KEV |
| [secrets-leak-guard](https://github.com/hustlerx01/secrets-leak-guard) | gitleaks config with custom rules for Indian and fintech secrets, tested like code |
| [ansible-cis-ubuntu](https://github.com/hustlerx01/ansible-cis-ubuntu) | Ansible role applying a tested subset of CIS Level 1 hardening on Ubuntu, with an audit script |
| [Automated-Security-Pipeline-DevSecOps](https://github.com/hustlerx01/Automated-Security-Pipeline-DevSecOps) | Jenkins DevSecOps pipeline: Maven/JUnit, SonarQube quality gate, Trivy image gate, Vault secrets, Docker Hub and Minikube deploy |

### 🤖 AI Security

| Project | What it does |
|---|---|
| [rag-redteam](https://github.com/hustlerx01/rag-redteam) | Indirect prompt-injection harness against a local RAG app, with three defenses measured before and after |
| [indicguard](https://github.com/hustlerx01/indicguard) | Prompt-injection detection for Hindi, Hinglish and Marathi inputs, with a benchmark |
| [llm-redactor](https://github.com/hustlerx01/llm-redactor) | FastAPI middleware that redacts PII and secrets from LLM output |
| [mcp-audit-lite](https://github.com/hustlerx01/mcp-audit-lite) | Static scanner for MCP server manifests: tool poisoning, hardcoded secrets and risky permissions |
| [l1-copilot](https://github.com/hustlerx01/l1-copilot) | Local-LLM triage helper for Wazuh and SSH alerts, with input sanitisation against prompt injection |

### ⚙️ DevOps / SRE / NOC / QA

| Project | What it does |
|---|---|
| [slo-lab](https://github.com/hustlerx01/slo-lab) | Multi-window multi-burn-rate SLO alerts, unit-tested with promtool and chaos-tested |
| [noc-probe-dashboard](https://github.com/hustlerx01/noc-probe-dashboard) | NOC monitoring with probe exporters, Prometheus alert rules and Grafana dashboards |
| [log-pipeline-lab](https://github.com/hustlerx01/log-pipeline-lab) | Fluent Bit to Loki log pipeline with parsing, enrichment and LogQL alert rules |
| [runbook-bot](https://github.com/hustlerx01/runbook-bot) | runbook-bot: Alertmanager alert -> allow-listed diagnostics -> Markdown postmortem |
| [chaos-kit](https://github.com/hustlerx01/chaos-kit) | Fault-injection kit for a sample microservice (latency, errors, outages) with measured results |
| [bluegreen-deploy](https://github.com/hustlerx01/bluegreen-deploy) | Blue/green deployment with GitHub Actions, Docker and Nginx, with health-checked automatic rollback |
| [gitops-homelab](https://github.com/hustlerx01/gitops-homelab) | ArgoCD app-of-apps for a security stack, validated offline with kustomize and kubeconform |
| [api-qa-suite](https://github.com/hustlerx01/api-qa-suite) | API QA suite: pytest + schemathesis + OWASP API Top 10 checks |

### 🔐 Application Security

| Project | What it does |
|---|---|
| [secure-shortener](https://github.com/hustlerx01/secure-shortener) | Secure URL shortener API: FastAPI, auth, rate limiting, OWASP-mapped tests |
| [spring-secure-api](https://github.com/hustlerx01/spring-secure-api) | Incident-ticket CRUD REST API in Java 17 / Spring Boot 3 with JWT, RBAC and IDOR protection |
| [webhook-payment-security-lab](https://github.com/hustlerx01/webhook-payment-security-lab) | Test-mode webhook receiver: HMAC signature checks, replay protection and idempotency keys |
| [webvuln-scanner](https://github.com/hustlerx01/webvuln-scanner) | CLI that checks security headers, cookie flags and TLS configuration of sites you own |
| [Browser-Autofill-Danger](https://github.com/hustlerx01/Browser-Autofill-Danger) | Live demo of autofill phishing: off-screen form fields the browser autofills without the user seeing them |

## 📜 Certifications
| Certification | Issuer | Date |
|---|---|---|
| Certified Ethical Hacker (CEH) Practical | EC-Council | Oct 2025 |
| Foundation Threat Intelligence Analyst | arcX | Mar 2025 |
| Certified AppSec Practitioner (CAP) | The SecOps Group | Mar 2024 |
| Microsoft Azure Fundamentals (AZ-900) | Microsoft | Feb 2024 |
| Advent of Cyber 2024 | TryHackMe | Dec 2024 |

## 🏁 CTFs & labs
- **CloudSEK CTF 2025** — 13th place
- **CTF Player & Security Researcher**, Hack The Box & TryHackMe (Aug 2025 – present)
- **ServiceNow** internship

## 🧰 Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Frameworks**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Cloud & IaC**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Checkov](https://img.shields.io/badge/Checkov-5C4EE5?style=flat-square&logo=paloaltonetworks&logoColor=white)

**Containers & CI/CD**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Kyverno](https://img.shields.io/badge/Kyverno-1E90FF?style=flat-square&logo=kubernetes&logoColor=white) ![OPA](https://img.shields.io/badge/OPA-566366?style=flat-square&logo=openpolicyagent&logoColor=white)

**Security & Detection**  
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=wazuh&logoColor=white) ![Suricata](https://img.shields.io/badge/Suricata-EF3B24?style=flat-square&logo=suricata&logoColor=white) ![Zeek](https://img.shields.io/badge/Zeek-2C3E50?style=flat-square&logo=zeek&logoColor=white) ![Sigma](https://img.shields.io/badge/Sigma-0B5394?style=flat-square&logo=sigma&logoColor=white) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT&CK-C0392B?style=flat-square&logo=mitre&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=trivy&logoColor=white) ![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-00549E?style=flat-square&logo=zap&logoColor=white) ![cosign](https://img.shields.io/badge/cosign-4051B5?style=flat-square&logo=sigstore&logoColor=white) ![gitleaks](https://img.shields.io/badge/gitleaks-E34F26?style=flat-square&logo=git&logoColor=white)

**Observability**  
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white) ![Fluent Bit](https://img.shields.io/badge/Fluent%20Bit-49BDA5?style=flat-square&logo=fluentbit&logoColor=white)

**Platforms**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

## 📫 Contact
[![Portfolio](https://img.shields.io/badge/Portfolio-hustlerx.si-000000?style=flat-square&logo=vercel&logoColor=white)](https://hustlerx.si)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hustlerx-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hustlerx)
[![Discord](https://img.shields.io/badge/Discord-message-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/974323061547479120)
[![Email](https://img.shields.io/badge/Email-ansar%40hustlerx.si-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ansar@hustlerx.si)
