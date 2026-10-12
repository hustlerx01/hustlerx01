<div align="center">

<img src="./assets/banner.svg" alt="root@hustlerx:~# whoami — Ansar Shaikh // SOC · Cloud Security · Detection Engineering" width="100%"/>

<br/>

[![Typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1000&color=A78BFA&center=true&vCenter=true&width=720&lines=security+engineer+%C2%B7+detection%2C+cloud+%26+AI+security;I+build+small+security+tools+and+test+them;then+I+write+down+what+they+missed)](https://github.com/hustlerx01)

<br/>

<a href="https://hustlerx.si"><img src="https://img.shields.io/badge/-hustlerx.si-0a0612?style=flat-square&logo=firefoxbrowser&logoColor=A78BFA&labelColor=1a0f2e"/></a>
&nbsp;
<img src="https://img.shields.io/badge/CEH-Practical-432874?style=flat-square&logo=eccouncil&logoColor=E8D5B7&labelColor=1a0f2e"/>
&nbsp;
<img src="https://img.shields.io/github/followers/hustlerx01?style=flat-square&color=432874&labelColor=1a0f2e&logo=github&logoColor=A78BFA&label=followers"/>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=hustlerx01&style=flat-square&color=432874&labelColor=1a0f2e&label=visitors"/>

</div>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;About

> Security engineer in **Pune, India**, working on detection, cloud and AI security.

I build small security tools, test them, and write down what they missed.

```bash
ansar@hustlerx:~$ cat about.txt
name      : Ansar Shaikh
location  : Pune, India
education : B.E. Information Technology (2025), Honours in Cybersecurity, CGPA 8.38
certs     : CEH Practical (EC-Council)
looking   : SOC / detection engineering, cloud security, AI security roles
```

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Journey

<div align="center">
<img src="./assets/journey.svg" alt="Journey timeline: 2024 to now" width="100%"/>
</div>

<details>
<summary><sub>&nbsp;view as table</sub></summary>

| When | What |
|:---:|:---|
| May – Jun 2024 | ServiceNow System Administrator virtual internship (AICTE) |
| 2025 | B.E. Information Technology, Honours in Cybersecurity, CGPA 8.38 |
| Aug 2025 → now | CTF Player and Security Researcher, Hack The Box & TryHackMe |
| Oct 2025 | CEH Practical, EC-Council |

</details>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Pick a role

| Role | Page |
|---|---|
| Security (SOC, VAPT and AI security combined) | [hustlerx.si/security](https://hustlerx.si/security) |
| SOC analyst (L1/L2) | [hustlerx.si/soc](https://hustlerx.si/soc) |
| Cloud security & DevSecOps | [hustlerx.si/cloud](https://hustlerx.si/cloud) |
| DevOps, SRE & NOC | [hustlerx.si/devops](https://hustlerx.si/devops) |
| AI security | [hustlerx.si/ai-security](https://hustlerx.si/ai-security) |
| VAPT, penetration testing & AppSec | [hustlerx.si/vapt](https://hustlerx.si/vapt) |
| Software engineering & QA | [hustlerx.si/swe](https://hustlerx.si/swe) |

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Featured projects

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
| [secrets-leak-guard](https://github.com/hustlerx01/secrets-leak-guard) | 10 TP, 0 FP, 0 FN | gitleaks rules for Indian formats (Razorpay keys, Aadhaar), a pre-commit hook that blocked a staged token, and a history scan. |
| [vulnops](https://github.com/hustlerx01/vulnops) | 355 findings to 185 | Merges Trivy, Grype and ZAP output, removes cross-tool duplicates and ranks by CISA KEV, EPSS and CVSS. |

### AI security

| Project | Result | What it is |
|---|---|---|
| [rag-redteam](https://github.com/hustlerx01/rag-redteam) | Injection success 3/8 to 1/8 | Indirect prompt-injection tests against a local RAG app on qwen2.5:1.5b with three defences. |
| [mcp-audit-lite](https://github.com/hustlerx01/mcp-audit-lite) | 19 findings, 0 on clean servers | Static scanner for MCP server manifests and source: tool poisoning, hardcoded secrets, shell=True and risky permissions. |
| [indicguard](https://github.com/hustlerx01/indicguard) | Hindi and Marathi injections | Prompt-injection detection for Hindi, Hinglish and Marathi input. |
| [llm-redactor](https://github.com/hustlerx01/llm-redactor) | Found and fixed a card regex bug | FastAPI middleware that redacts PII and secrets, including PAN, UPI and IFSC, from LLM output. |

**Also built:** [hardened-aws-web-tier](https://github.com/hustlerx01/hardened-aws-web-tier), [mini-cspm-aws](https://github.com/hustlerx01/mini-cspm-aws), [k8s-policy-pack](https://github.com/hustlerx01/k8s-policy-pack), [iac-scan-bench](https://github.com/hustlerx01/iac-scan-bench), [signed-by-default](https://github.com/hustlerx01/signed-by-default), [slo-lab](https://github.com/hustlerx01/slo-lab), [bluegreen-deploy](https://github.com/hustlerx01/bluegreen-deploy), [chaos-kit](https://github.com/hustlerx01/chaos-kit), [log-pipeline-lab](https://github.com/hustlerx01/log-pipeline-lab), [spring-secure-api](https://github.com/hustlerx01/spring-secure-api), [pcap-hunter](https://github.com/hustlerx01/pcap-hunter), [ioc-aggregator](https://github.com/hustlerx01/ioc-aggregator)

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Experience & certifications

| When | What |
|---|---|
| Aug 2025 → now | **CTF Player and Security Researcher**, [Hack The Box](https://www.hackthebox.com/) & [TryHackMe](https://tryhackme.com/) |
| May – Jun 2024 | ServiceNow System Administrator virtual internship (AICTE) |

| Certification | Issuer | Date |
|---|---|---|
| Certified Ethical Hacker (CEH) Practical | EC-Council | Oct 2025 |
| arcX Foundation Threat Intelligence Analyst | arcX | Mar 2025 |
| Certified AppSec Practitioner (CAP) | The SecOps Group | Mar 2024 |
| Microsoft Azure Fundamentals (AZ-900) | Microsoft | Feb 2024 |

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-0a0612?style=flat-square&logo=python&logoColor=A78BFA) ![Bash](https://img.shields.io/badge/Bash-0a0612?style=flat-square&logo=gnubash&logoColor=A78BFA) ![Java](https://img.shields.io/badge/Java-0a0612?style=flat-square&logo=openjdk&logoColor=A78BFA) ![JavaScript](https://img.shields.io/badge/JavaScript-0a0612?style=flat-square&logo=javascript&logoColor=A78BFA) ![TypeScript](https://img.shields.io/badge/TypeScript-0a0612?style=flat-square&logo=typescript&logoColor=A78BFA)

**Frameworks**  
![FastAPI](https://img.shields.io/badge/FastAPI-1a0f2e?style=flat-square&logo=fastapi&logoColor=A78BFA) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-1a0f2e?style=flat-square&logo=springboot&logoColor=A78BFA) ![React](https://img.shields.io/badge/React-1a0f2e?style=flat-square&logo=react&logoColor=A78BFA) ![pytest](https://img.shields.io/badge/pytest-1a0f2e?style=flat-square&logo=pytest&logoColor=A78BFA)

**Cloud & IaC**  
![AWS](https://img.shields.io/badge/AWS-2d1b4e?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-2d1b4e?style=flat-square&logo=terraform&logoColor=A78BFA) ![Ansible](https://img.shields.io/badge/Ansible-2d1b4e?style=flat-square&logo=ansible&logoColor=A78BFA) ![Checkov](https://img.shields.io/badge/Checkov-2d1b4e?style=flat-square&logo=paloaltonetworks&logoColor=A78BFA)

**Containers & CI/CD**  
![Docker](https://img.shields.io/badge/Docker-432874?style=flat-square&logo=docker&logoColor=E8D5B7) ![Kubernetes](https://img.shields.io/badge/Kubernetes-432874?style=flat-square&logo=kubernetes&logoColor=E8D5B7) ![Argo CD](https://img.shields.io/badge/Argo%20CD-432874?style=flat-square&logo=argo&logoColor=E8D5B7) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-432874?style=flat-square&logo=githubactions&logoColor=E8D5B7) ![Jenkins](https://img.shields.io/badge/Jenkins-432874?style=flat-square&logo=jenkins&logoColor=E8D5B7) ![Kyverno](https://img.shields.io/badge/Kyverno-432874?style=flat-square&logo=kubernetes&logoColor=E8D5B7) ![OPA](https://img.shields.io/badge/OPA-432874?style=flat-square)

**Security & Detection**  
![Wazuh](https://img.shields.io/badge/Wazuh-0a0612?style=flat-square) ![Suricata](https://img.shields.io/badge/Suricata-0a0612?style=flat-square) ![Zeek](https://img.shields.io/badge/Zeek-0a0612?style=flat-square) ![Sigma](https://img.shields.io/badge/Sigma-0a0612?style=flat-square) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-0a0612?style=flat-square) ![Trivy](https://img.shields.io/badge/Trivy-0a0612?style=flat-square&logo=trivy&logoColor=A78BFA) ![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-0a0612?style=flat-square&logo=zap&logoColor=A78BFA) ![cosign](https://img.shields.io/badge/cosign-0a0612?style=flat-square) ![gitleaks](https://img.shields.io/badge/gitleaks-0a0612?style=flat-square&logo=git&logoColor=A78BFA)

**Observability**  
![Prometheus](https://img.shields.io/badge/Prometheus-1a0f2e?style=flat-square&logo=prometheus&logoColor=A78BFA) ![Grafana](https://img.shields.io/badge/Grafana-1a0f2e?style=flat-square&logo=grafana&logoColor=A78BFA) ![Loki](https://img.shields.io/badge/Loki-1a0f2e?style=flat-square&logo=grafana&logoColor=A78BFA) ![Fluent Bit](https://img.shields.io/badge/Fluent%20Bit-1a0f2e?style=flat-square&logo=fluentbit&logoColor=A78BFA)

**Platforms**  
![Linux](https://img.shields.io/badge/Linux-2d1b4e?style=flat-square&logo=linux&logoColor=A78BFA) ![Nginx](https://img.shields.io/badge/Nginx-2d1b4e?style=flat-square&logo=nginx&logoColor=A78BFA)

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Stats

<div align="center">

<img height="180" src="https://github-stats-extended.vercel.app/api?username=hustlerx01&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0a0612&title_color=E8D5B7&text_color=C9B8D9&icon_color=A78BFA&hide=contribs,prs" alt="GitHub stats"/>
<img height="180" src="https://github-stats-extended.vercel.app/api/top-langs/?username=hustlerx01&layout=compact&hide_border=true&langs_count=8&bg_color=0a0612&title_color=E8D5B7&text_color=C9B8D9&icon_color=A78BFA" alt="top languages"/>

<img width="100%" src="https://streak-stats.demolab.com/?user=hustlerx01&hide_border=true&background=0a0612&stroke=432874&ring=A78BFA&fire=E8D5B7&currStreakLabel=E8D5B7&sideNums=C9B8D9&currStreakNum=E8D5B7&dates=C9B8D9&sideLabels=C9B8D9" alt="streak"/>

<img width="100%" src="https://github-profile-trophy-unserori.vercel.app/?username=hustlerx01&theme=darkhub&no-frame=true&column=7&margin-w=8&margin-h=8" alt="trophies"/>

<img width="100%" src="https://raw.githubusercontent.com/hustlerx01/hustlerx01/output/github-contribution-grid-snake-dark.svg" alt="snake eating contributions"/>

</div>

<img src="./assets/divider.svg" width="100%"/>

<img src="./assets/quote.svg" width="100%" alt="a short security note"/>

<img src="./assets/divider.svg" width="100%"/>

## &nbsp;Contact

<div align="center">
<table><tr>
<td align="center" width="20%"><a href="https://hustlerx.si"><img src="https://api.iconify.design/lucide/globe.svg?color=%23a78bfa" width="30" height="30"/><br/><b>website</b><br/><sub>hustlerx.si</sub></a></td>
<td align="center" width="20%"><a href="https://www.linkedin.com/in/hustlerx"><img src="https://api.iconify.design/lucide/linkedin.svg?color=%23a78bfa" width="30" height="30"/><br/><b>linkedin</b><br/><sub>in/hustlerx</sub></a></td>
<td align="center" width="20%"><a href="https://github.com/hustlerx01"><img src="https://api.iconify.design/lucide/github.svg?color=%23a78bfa" width="30" height="30"/><br/><b>github</b><br/><sub>@hustlerx01</sub></a></td>
<td align="center" width="20%"><a href="mailto:ansarshaikh@hustlerx.si"><img src="https://api.iconify.design/lucide/mail.svg?color=%23a78bfa" width="30" height="30"/><br/><b>email</b><br/><sub>ansarshaikh@hustlerx.si</sub></a></td>
<td align="center" width="20%"><a href="https://discord.com/users/974323061547479120"><img src="https://api.iconify.design/lucide/message-circle.svg?color=%23a78bfa" width="30" height="30"/><br/><b>discord</b><br/><sub>message me</sub></a></td>
</tr></table>
</div>

<br/>

<img src="./assets/footer.svg" width="100%"/>
