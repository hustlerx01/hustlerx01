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
| Security (SOC, VAPT and AI security combined) | [hustlerx.si/security](https://hustlerx.si/security) |
| SOC analyst (L1/L2) | [hustlerx.si/soc](https://hustlerx.si/soc) |
| Cloud security & DevSecOps | [hustlerx.si/cloud](https://hustlerx.si/cloud) |
| DevOps, SRE & NOC | [hustlerx.si/devops](https://hustlerx.si/devops) |
| AI security | [hustlerx.si/ai-security](https://hustlerx.si/ai-security) |
| VAPT, penetration testing & AppSec | [hustlerx.si/vapt](https://hustlerx.si/vapt) |
| Software engineering & QA | [hustlerx.si/swe](https://hustlerx.si/swe) |

## Featured projects

### SOC & detection

| Project | Result | What it is |
|---|---|---|
| [siem-lab](https://github.com/hustlerx01/siem-lab) | 5/5 Suricata rules fired | Wazuh and Suricata in Docker with custom rules mapped to MITRE ATT&CK, replayed against public EVTX attack samples and a generated pcap. |
| [detection-rules-as-code](https://github.com/hustlerx01/detection-rules-as-code) | 16/16 TP, 0/16 FP | 10 Sigma rules, each with true- and false-positive sample events, a linter and a CI gate. |
| [soc-honeypot-lab](https://github.com/hustlerx01/soc-honeypot-lab) | 112 TP, 0 FP, 30 FN | Honeypot log lab with Sentinel-style detections written as KQL, Sigma and Python that run locally, scored against labelled synthetic events. |
| [phishdesk-in](https://github.com/hustlerx01/phishdesk-in) | SPF, DKIM, DMARC + UPI lures | Explains why an .eml looks like phishing: header authentication checks plus Indian bank and UPI lure rules, tested on 69 synthetic lab emails. |

### VAPT & AppSec

| Project | Result | What it is |
|---|---|---|
| [webvuln-scanner](https://github.com/hustlerx01/webvuln-scanner) | Flags TLS 1.0/1.1, weak cookies | CLI that checks security headers, cookie flags and TLS on sites you own and grades them. |
| [secure-shortener](https://github.com/hustlerx01/secure-shortener) | OWASP Top 10, 24 tests | URL shortener where every control maps to an OWASP Top 10 category with a named test. |
| [api-qa-suite](https://github.com/hustlerx01/api-qa-suite) | 6/6 seeded defects caught | Security and functional tests for an API with 6 seeded OWASP API Top 10 defects: 9 tests fail on the vulnerable build, all 28 pass on the fixed one. |
| [Endpoint-Finder](https://github.com/hustlerx01/Endpoint-Finder) | One-click endpoint recon | Bookmarklet that lists endpoint URLs on a page by recursively fetching its scripts. |

### AI security

| Project | Result | What it is |
|---|---|---|
| [rag-redteam](https://github.com/hustlerx01/rag-redteam) | Injection success 3/8 to 1/8 | Indirect prompt-injection tests against a local RAG app on qwen2.5:1.5b with three defences. |
| [mcp-audit-lite](https://github.com/hustlerx01/mcp-audit-lite) | 19 findings, 0 on clean servers | Static scanner for MCP server manifests and source: tool poisoning, hardcoded secrets, shell=True and risky permissions. |
| [indicguard](https://github.com/hustlerx01/indicguard) | Hindi and Marathi injections | Prompt-injection detection for Hindi, Hinglish and Marathi input. |
| [llm-redactor](https://github.com/hustlerx01/llm-redactor) | Found and fixed a card regex bug | FastAPI middleware that redacts PII and secrets, including PAN, UPI and IFSC, from LLM output. |

**Also built (cloud and DevOps):** [hardened-aws-web-tier](https://github.com/hustlerx01/hardened-aws-web-tier), [mini-cspm-aws](https://github.com/hustlerx01/mini-cspm-aws), [k8s-policy-pack](https://github.com/hustlerx01/k8s-policy-pack), [iac-scan-bench](https://github.com/hustlerx01/iac-scan-bench), [signed-by-default](https://github.com/hustlerx01/signed-by-default), [slo-lab](https://github.com/hustlerx01/slo-lab), [bluegreen-deploy](https://github.com/hustlerx01/bluegreen-deploy), [chaos-kit](https://github.com/hustlerx01/chaos-kit), [log-pipeline-lab](https://github.com/hustlerx01/log-pipeline-lab), [spring-secure-api](https://github.com/hustlerx01/spring-secure-api)

## Certifications

| Certification | Issuer | Date |
|---|---|---|
| Certified Ethical Hacker (CEH) Practical | EC-Council | Oct 2025 |
| arcX Foundation Threat Intelligence Analyst | arcX | Mar 2025 |
| Certified AppSec Practitioner (CAP) | The SecOps Group | Mar 2024 |
| Microsoft Azure Fundamentals (AZ-900) | Microsoft | Feb 2024 |

## CTFs and labs

- CloudSEK CTF 2025: 13th place
- [Hack The Box](https://www.hackthebox.com/) and [TryHackMe](https://tryhackme.com/) labs, Aug 2025 to now
- ServiceNow System Administrator virtual internship (AICTE), May to Jun 2024

## 🧰 Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Frameworks**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Cloud & IaC**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Checkov](https://img.shields.io/badge/Checkov-5C4EE5?style=flat-square&logo=paloaltonetworks&logoColor=white)

**Containers & CI/CD**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![Kyverno](https://img.shields.io/badge/Kyverno-1E90FF?style=flat-square&logo=kubernetes&logoColor=white) ![OPA](https://img.shields.io/badge/OPA-566366?style=flat-square)

**Security & Detection**  
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square) ![Suricata](https://img.shields.io/badge/Suricata-EF3B24?style=flat-square) ![Zeek](https://img.shields.io/badge/Zeek-2C3E50?style=flat-square) ![Sigma](https://img.shields.io/badge/Sigma-0B5394?style=flat-square) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C0392B?style=flat-square) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=trivy&logoColor=white) ![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-00549E?style=flat-square&logo=zap&logoColor=white) ![cosign](https://img.shields.io/badge/cosign-4051B5?style=flat-square) ![gitleaks](https://img.shields.io/badge/gitleaks-E34F26?style=flat-square&logo=git&logoColor=white)

**Observability**  
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square&logo=grafana&logoColor=white) ![Fluent Bit](https://img.shields.io/badge/Fluent%20Bit-49BDA5?style=flat-square&logo=fluentbit&logoColor=white)

**Platforms**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

## 📫 Contact
[![Portfolio](https://img.shields.io/badge/Portfolio-hustlerx.si-000000?style=flat-square&logo=vercel&logoColor=white)](https://hustlerx.si)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hustlerx-0A66C2?style=flat-square)](https://www.linkedin.com/in/hustlerx)
[![Hack The Box](https://img.shields.io/badge/Hack%20The%20Box-profile-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)](https://www.hackthebox.com/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-profile-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/)
[![Discord](https://img.shields.io/badge/Discord-message-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/974323061547479120)
[![Email](https://img.shields.io/badge/Email-ansar%40hustlerx.si-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ansar@hustlerx.si)
