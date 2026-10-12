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

### SOC & Detection

| Project | Result |
|---|---|
| [siem-lab](https://github.com/hustlerx01/siem-lab) | Wazuh + Suricata lab with ATT&CK-mapped rules. After a decoder-routing fix, every custom Wazuh rule with a test event fires; 5/5 Suricata rules fired; 24 pytest checks pass |
| [detection-rules-as-code](https://github.com/hustlerx01/detection-rules-as-code) | 10 Sigma rules with TP/FP tests and a CI gate. 10/10 convert to Splunk SPL; 16/16 TP hit, 0/16 FP |
| [evtx-triage](https://github.com/hustlerx01/evtx-triage) | EVTX triage with 14 ATT&CK-mapped rules. 11/11 public attack samples flagged (tuned on the same samples) |
| [phishdesk-in](https://github.com/hustlerx01/phishdesk-in) | Explainable .eml phishing analyser with Indian bank/UPI lure rules. Precision 0.909, recall 0.833 on 69 synthetic emails |

### Cloud & DevSecOps

| Project | Result |
|---|---|
| [hardened-aws-web-tier](https://github.com/hustlerx01/hardened-aws-web-tier) | Terraform AWS web tier: private EC2, IMDSv2, SSM, CloudTrail, GuardDuty, OIDC. tfsec 30 passed, 0 open; Trivy 0 misconfigurations (static checks, not applied) |
| [signed-by-default](https://github.com/hustlerx01/signed-by-default) | cosign signing, SBOM attestation, SLSA provenance and Kyverno admission. Offline end-to-end run passes; keyless CI path not run yet |
| [Automated-Security-Pipeline-DevSecOps](https://github.com/hustlerx01/Automated-Security-Pipeline-DevSecOps) | Jenkins pipeline adapted from an existing project: SonarQube quality gate, Trivy scan, Kubernetes deploy |
| [runbook-bot](https://github.com/hustlerx01/runbook-bot) | Alertmanager alert to allow-listed diagnostics and a draft postmortem. 4/5 sample alerts matched; command-injection label blocked; 8 tests pass |

### AI Security & AppSec

| Project | Result |
|---|---|
| [rag-redteam](https://github.com/hustlerx01/rag-redteam) | Indirect prompt-injection tests on a local RAG app. Attack success on qwen2.5:1.5b fell from 3/8 to 1/8; only the output guard helped |
| [l1-copilot](https://github.com/hustlerx01/l1-copilot) | Local-LLM triage for Wazuh SSH alerts. Rule baseline F1 0.911 on 100 synthetic alerts; the 1.5B model reached recall 0.105 |
| [api-qa-suite](https://github.com/hustlerx01/api-qa-suite) | API tests that catch 6/6 seeded OWASP API defects (9 failures) and pass 28/28 on the fixed build |
| [secure-shortener](https://github.com/hustlerx01/secure-shortener) | URL shortener with each control mapped to an OWASP Top 10 test. 24 tests pass; metadata URL blocked with 400, brute force gets 429 |

**More on GitHub:** [soar-mini](https://github.com/hustlerx01/soar-mini), [mini-cspm-aws](https://github.com/hustlerx01/mini-cspm-aws), [k8s-policy-pack](https://github.com/hustlerx01/k8s-policy-pack), [iac-scan-bench](https://github.com/hustlerx01/iac-scan-bench), [indicguard](https://github.com/hustlerx01/indicguard), [llm-redactor](https://github.com/hustlerx01/llm-redactor), [mcp-audit-lite](https://github.com/hustlerx01/mcp-audit-lite), [pcap-hunter](https://github.com/hustlerx01/pcap-hunter), [spring-secure-api](https://github.com/hustlerx01/spring-secure-api), [slo-lab](https://github.com/hustlerx01/slo-lab), [SSH-Log-Alert](https://github.com/hustlerx01/SSH-Log-Alert)

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
