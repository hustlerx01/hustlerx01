<p align="center">
  <img src="assets/banner.svg" alt="root@hustlerx:~# whoami — Ansar Shaikh // SOC · Cloud Security · Detection Engineering" width="100%" />
</p>

**Security engineer focused on detection, cloud and AI security.** I build small security tools, test them, and write down what they missed.

```bash
ansar@hustlerx:~$ cat about.txt
name      : Ansar Shaikh
location  : Pune, India
education : B.E. Information Technology (2025), Honours in Cybersecurity
certs     : CEH Practical (EC-Council)
ctf       : CloudSEK CTF 2025, 13th place
looking   : SOC / detection engineering, cloud security, AI security roles
```

## Pick a role

| Role | Page |
|---|---|
| SOC analyst (L1/L2) | [hustlerx.si/soc](https://hustlerx.si/soc) |
| Cloud security & DevSecOps | [hustlerx.si/cloud](https://hustlerx.si/cloud) |
| DevOps, SRE & NOC | [hustlerx.si/devops](https://hustlerx.si/devops) |
| AI security | [hustlerx.si/ai-security](https://hustlerx.si/ai-security) |
| VAPT, penetration testing & AppSec | [hustlerx.si/vapt](https://hustlerx.si/vapt) |
| Software engineering & QA | [hustlerx.si/swe](https://hustlerx.si/swe) |

## Featured projects

### SOC analyst (L1/L2)

| Project | Result | What it is |
|---|---|---|
| [siem-lab](https://github.com/hustlerx01/siem-lab) | 5/5 Suricata rules fired | Wazuh and Suricata in Docker with custom rules mapped to MITRE ATT&CK, replayed against public EVTX attack samples and a generated pcap. |
| [detection-rules-as-code](https://github.com/hustlerx01/detection-rules-as-code) | 16/16 TP, 0/16 FP | 10 Sigma rules, each with true- and false-positive sample events, a linter and a CI gate. |
| [soc-honeypot-lab](https://github.com/hustlerx01/soc-honeypot-lab) | 112 TP, 0 FP, 30 FN | Honeypot log lab with Sentinel-style detections written as KQL, Sigma and Python that run locally, scored against labelled synthetic events. |
| [phishdesk-in](https://github.com/hustlerx01/phishdesk-in) | SPF, DKIM, DMARC + UPI lures | Explains why an .eml looks like phishing: header authentication checks plus Indian bank and UPI lure rules, tested on 69 synthetic lab emails. |
| [soar-mini](https://github.com/hustlerx01/soar-mini) | 6/6 alert verdicts | IOC enrichment playbook: refangs indicators, queries VirusTotal, AbuseIPDB and URLhaus (mocked offline), scores them and asks a human before any block. |

### Cloud security & DevSecOps

| Project | Result | What it is |
|---|---|---|
| [hardened-aws-web-tier](https://github.com/hustlerx01/hardened-aws-web-tier) | tfsec 30 passed, 0 open | Terraform for an AWS web tier where only the load balancer is public: private EC2, IMDSv2, SSM instead of SSH, CloudTrail, GuardDuty, KMS and a repo-scoped GitHub OIDC role. |
| [mini-cspm-aws](https://github.com/hustlerx01/mini-cspm-aws) | 20 CIS AWS checks | Posture checks in boto3 mapped to CIS AWS Foundations controls, run against a moto-mocked account. |
| [k8s-policy-pack](https://github.com/hustlerx01/k8s-policy-pack) | 48/48 Kyverno tests pass | Six Pod Security controls written in both Kyverno and OPA/Rego with a parity test. |
| [iac-scan-bench](https://github.com/hustlerx01/iac-scan-bench) | Checkov 10/11 planted | Plants 11 Terraform misconfigurations and measures what Checkov, tfsec and my own Rego rules actually catch. |
| [signed-by-default](https://github.com/hustlerx01/signed-by-default) | Only signed images admitted | cosign signing, SBOM attestation and SLSA provenance for a small Go service, with Kyverno admitting only signed images. |

### DevOps, SRE & NOC

| Project | Result | What it is |
|---|---|---|
| [slo-lab](https://github.com/hustlerx01/slo-lab) | 6 promtool scenarios pass | Multi-window, multi-burn-rate SLO alerts for a synthetic checkout service. |
| [bluegreen-deploy](https://github.com/hustlerx01/bluegreen-deploy) | 501 requests, 0 errors | Blue/green deploy with GitHub Actions, Docker and Nginx. |
| [chaos-kit](https://github.com/hustlerx01/chaos-kit) | p95 662 ms to 160 ms | Fault injection against a sample service. |
| [log-pipeline-lab](https://github.com/hustlerx01/log-pipeline-lab) | 3859 records, 0 dropped | Fluent Bit to Loki pipeline with parsing, enrichment and 4 LogQL alert rules, all loaded by the Loki ruler. |
| [noc-probe-dashboard](https://github.com/hustlerx01/noc-probe-dashboard) | promtool rule tests pass | NOC monitoring with a small TCP, HTTP and ICMP probe exporter, Prometheus alert rules for target down, flapping, reboots and link saturation, and Grafana dashboards. |

### AI security

| Project | Result | What it is |
|---|---|---|
| [rag-redteam](https://github.com/hustlerx01/rag-redteam) | Injection success 3/8 to 1/8 | Indirect prompt-injection tests against a local RAG app on qwen2.5:1.5b with three defences. |
| [mcp-audit-lite](https://github.com/hustlerx01/mcp-audit-lite) | 19 findings, 0 on clean servers | Static scanner for MCP server manifests and source: tool poisoning, hardcoded secrets, shell=True and risky permissions. |
| [indicguard](https://github.com/hustlerx01/indicguard) | Hindi and Marathi injections | Prompt-injection detection for Hindi, Hinglish and Marathi input. |
| [llm-redactor](https://github.com/hustlerx01/llm-redactor) | Found and fixed a card regex bug | FastAPI middleware that redacts PII and secrets, including PAN, UPI and IFSC, from LLM output. |
| [l1-copilot](https://github.com/hustlerx01/l1-copilot) | Local-LLM alert triage | Sends Wazuh SSH alerts to a local LLM, with input sanitising against prompt injection. |

### VAPT, penetration testing & AppSec

| Project | Result | What it is |
|---|---|---|
| [webvuln-scanner](https://github.com/hustlerx01/webvuln-scanner) | Flags TLS 1.0/1.1, weak cookies | CLI that checks security headers, cookie flags and TLS on sites you own and grades them. |
| [secure-shortener](https://github.com/hustlerx01/secure-shortener) | OWASP Top 10, 24 tests | URL shortener where every control maps to an OWASP Top 10 category with a named test. |
| [api-qa-suite](https://github.com/hustlerx01/api-qa-suite) | 6/6 seeded defects caught | Security and functional tests for an API with 6 seeded OWASP API Top 10 defects: 9 tests fail on the vulnerable build, all 28 pass on the fixed one. |
| [Endpoint-Finder](https://github.com/hustlerx01/Endpoint-Finder) | One-click endpoint recon | Bookmarklet that lists endpoint URLs on a page by recursively fetching its scripts. |
| [Browser-Autofill-Danger](https://github.com/hustlerx01/Browser-Autofill-Danger) | Exposes hidden autofill leaks | Live demo of autofill phishing: off-screen fields that the browser fills without the user seeing them. |

### Software engineering & QA

| Project | Result | What it is |
|---|---|---|
| [api-qa-suite](https://github.com/hustlerx01/api-qa-suite) | 6/6 seeded defects caught | pytest and schemathesis suite for an API with 6 seeded defects: 9 failures on the vulnerable build, 28 of 28 passing on the fixed build, stable across repeated runs. |
| [spring-secure-api](https://github.com/hustlerx01/spring-secure-api) | 25 tests, 0 failures | Incident-ticket REST API in Java 17 and Spring Boot 3 with JWT, RBAC and IDOR protection, tested with JUnit 5 and MockMvc. |
| [secure-shortener](https://github.com/hustlerx01/secure-shortener) | 24 tests pass | FastAPI URL shortener with auth and rate limiting, where each control has a named test. |
| [bluegreen-deploy](https://github.com/hustlerx01/bluegreen-deploy) | 501 requests, 0 errors | Blue/green deploys with GitHub Actions, Docker and Nginx, with an end-to-end test that switches versions under load. |
| [AWS-S3-Storage-Client](https://github.com/hustlerx01/AWS-S3-Storage-Client) | Expiring S3 share links | AeroVault: React and TypeScript S3 file manager with drag-and-drop uploads, previews and pre-signed share links. |

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| Certified Ethical Hacker (CEH) Practical | EC-Council | Oct 2025 |
| Foundation Threat Intelligence Analyst | arcX | Mar 2025 |
| Certified AppSec Practitioner (CAP) | The SecOps Group | Mar 2024 |
| Microsoft Azure Fundamentals (AZ-900) | Microsoft | Feb 2024 |

## CTFs and labs

- CloudSEK CTF 2025: 13th place
- Hack The Box and TryHackMe labs, Aug 2025 to now
- ServiceNow System Administrator virtual internship (AICTE), May to Jun 2024

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
