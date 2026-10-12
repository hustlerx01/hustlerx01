<div align="center">

<img src="./assets/banner.svg" alt="HUSTLERX: security researcher · CTF player · Pune" width="100%"/>

<a href="https://hustlerx.si"><img src="https://img.shields.io/badge/HUSTLERX.SI-0a0a0a?style=for-the-badge&logo=firefoxbrowser&logoColor=white"/></a>&nbsp;<img src="https://img.shields.io/badge/CEH-PRACTICAL-1a1a1a?style=for-the-badge&labelColor=0a0a0a"/>&nbsp;<img src="https://img.shields.io/github/followers/hustlerx01?style=for-the-badge&color=1a1a1a&labelColor=0a0a0a&logo=github&logoColor=white&label=followers"/>&nbsp;<img src="https://hits.sh/github.com/hustlerx01.svg?style=for-the-badge&label=visitors&color=1a1a1a&labelColor=0a0a0a"/>

</div>

<a id="about"></a>
<img src="./assets/h-about.svg" width="100%" alt="About"/>

> Security engineer in **Pune, India**, working on detection, cloud and AI security.

I build small security tools, test them, and write down what they missed.

<img src="./assets/status.svg" width="100%" alt="focus: detection, cloud, AI sec · tools: wazuh, sigma, suricata · cert: CEH Practical"/>

```bash
ansar@hustlerx:~$ cat about.txt
name      : Ansar Shaikh
location  : Pune, India
education : Sinhgad Institute of Technology & Science (SPPU), Pune
            B.E. IT, Cybersecurity honours, 2021-2025, CGPA 8.38
certs     : CEH Practical (EC-Council)
looking   : SOC / detection engineering, cloud security, AI security roles
```

<a id="journey"></a>
<img src="./assets/h-journey.svg" width="100%" alt="Journey"/>

<div align="center">
<img src="./assets/journey.svg" alt="HustlerX journey, 2021 to now" width="100%"/>
</div>

<details>
<summary><sub>&nbsp;view as table</sub></summary>

| When | What |
|:---:|:---|
| 2021 | Joined Sinhgad Institute of Technology & Science (SPPU), Pune: B.E. Information Technology, Honours in Cybersecurity |
| May – Jun 2024 | ServiceNow System Administrator virtual internship (AICTE) |
| Jul 2025 | Graduated B.E. IT, Cybersecurity honours, CGPA 8.38, no backlogs |
| Aug 2025 → now | CTF Player and Security Researcher, Hack The Box & TryHackMe |
| Oct 2025 | CEH Practical, EC-Council |

</details>

<a id="projects"></a>
<img src="./assets/h-projects.svg" width="100%" alt="Featured projects"/>

#### `SOC & DETECTION`

| Project | Result | What it is |
|---|---|---|
| [siem-lab](https://github.com/hustlerx01/siem-lab) | 5/5 Suricata rules fired | Wazuh and Suricata in Docker with custom rules mapped to MITRE ATT&CK, replayed against public EVTX attack samples and a generated pcap. |
| [detection-rules-as-code](https://github.com/hustlerx01/detection-rules-as-code) | 16/16 TP, 0/16 FP | 10 Sigma rules, each with true- and false-positive sample events, a linter and a CI gate. |
| [soc-honeypot-lab](https://github.com/hustlerx01/soc-honeypot-lab) | 112 TP, 0 FP, 30 FN | Honeypot log lab with Sentinel-style detections written as KQL, Sigma and Python that run locally, scored against labelled synthetic events. |
| [phishdesk-in](https://github.com/hustlerx01/phishdesk-in) | SPF, DKIM, DMARC + UPI lures | Explains why an .eml looks like phishing: header authentication checks plus Indian bank and UPI lure rules, tested on 69 synthetic lab emails. |

#### `VAPT & APPSEC`

| Project | Result | What it is |
|---|---|---|
| [webvuln-scanner](https://github.com/hustlerx01/webvuln-scanner) | Flags TLS 1.0/1.1, weak cookies | CLI that checks security headers, cookie flags and TLS on sites you own and grades them. |
| [secure-shortener](https://github.com/hustlerx01/secure-shortener) | OWASP Top 10, 24 tests | URL shortener where every control maps to an OWASP Top 10 category with a named test. |
| [api-qa-suite](https://github.com/hustlerx01/api-qa-suite) | 6/6 seeded defects caught | Security and functional tests for an API with 6 seeded OWASP API Top 10 defects: 9 tests fail on the vulnerable build, all 28 pass on the fixed one. |
| [secrets-leak-guard](https://github.com/hustlerx01/secrets-leak-guard) | 10 TP, 0 FP, 0 FN | gitleaks rules for Indian formats (Razorpay keys, Aadhaar), a pre-commit hook that blocked a staged token, and a history scan. |
| [vulnops](https://github.com/hustlerx01/vulnops) | 355 findings to 185 | Merges Trivy, Grype and ZAP output, removes cross-tool duplicates and ranks by CISA KEV, EPSS and CVSS. |

#### `AI SECURITY`

| Project | Result | What it is |
|---|---|---|
| [rag-redteam](https://github.com/hustlerx01/rag-redteam) | Injection success 3/8 to 1/8 | Indirect prompt-injection tests against a local RAG app on qwen2.5:1.5b with three defences. |
| [mcp-audit-lite](https://github.com/hustlerx01/mcp-audit-lite) | 19 findings, 0 on clean servers | Static scanner for MCP server manifests and source: tool poisoning, hardcoded secrets, shell=True and risky permissions. |
| [indicguard](https://github.com/hustlerx01/indicguard) | Hindi and Marathi injections | Prompt-injection detection for Hindi, Hinglish and Marathi input. |
| [llm-redactor](https://github.com/hustlerx01/llm-redactor) | Found and fixed a card regex bug | FastAPI middleware that redacts PII and secrets, including PAN, UPI and IFSC, from LLM output. |

**Also built:** [hardened-aws-web-tier](https://github.com/hustlerx01/hardened-aws-web-tier), [mini-cspm-aws](https://github.com/hustlerx01/mini-cspm-aws), [k8s-policy-pack](https://github.com/hustlerx01/k8s-policy-pack), [iac-scan-bench](https://github.com/hustlerx01/iac-scan-bench), [signed-by-default](https://github.com/hustlerx01/signed-by-default), [slo-lab](https://github.com/hustlerx01/slo-lab), [bluegreen-deploy](https://github.com/hustlerx01/bluegreen-deploy), [chaos-kit](https://github.com/hustlerx01/chaos-kit), [log-pipeline-lab](https://github.com/hustlerx01/log-pipeline-lab), [spring-secure-api](https://github.com/hustlerx01/spring-secure-api), [pcap-hunter](https://github.com/hustlerx01/pcap-hunter), [ioc-aggregator](https://github.com/hustlerx01/ioc-aggregator)

<a id="experience"></a>
<img src="./assets/h-experience.svg" width="100%" alt="Experience & certifications"/>

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

<a id="stack"></a>
<img src="./assets/h-stack.svg" width="100%" alt="Tech stack"/>

**Languages**  
![Python](https://img.shields.io/badge/Python-0a0a0a?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-0a0a0a?style=flat-square&logo=gnubash&logoColor=white) ![Java](https://img.shields.io/badge/Java-0a0a0a?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-0a0a0a?style=flat-square&logo=javascript&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-0a0a0a?style=flat-square&logo=typescript&logoColor=white)

**Frameworks**  
![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=flat-square&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-111111?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React-111111?style=flat-square&logo=react&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-111111?style=flat-square&logo=pytest&logoColor=white)

**Cloud & IaC**  
![AWS](https://img.shields.io/badge/AWS-1a1a1a?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-1a1a1a?style=flat-square&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-1a1a1a?style=flat-square&logo=ansible&logoColor=white) ![Checkov](https://img.shields.io/badge/Checkov-1a1a1a?style=flat-square&logo=paloaltonetworks&logoColor=white)

**Containers & CI/CD**  
![Docker](https://img.shields.io/badge/Docker-2a2a2a?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-2a2a2a?style=flat-square&logo=kubernetes&logoColor=white) ![Argo CD](https://img.shields.io/badge/Argo%20CD-2a2a2a?style=flat-square&logo=argo&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2a2a2a?style=flat-square&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-2a2a2a?style=flat-square&logo=jenkins&logoColor=white) ![Kyverno](https://img.shields.io/badge/Kyverno-2a2a2a?style=flat-square&logo=kubernetes&logoColor=white) ![OPA](https://img.shields.io/badge/OPA-2a2a2a?style=flat-square)

**Security & Detection**  
![Wazuh](https://img.shields.io/badge/Wazuh-0a0a0a?style=flat-square) ![Suricata](https://img.shields.io/badge/Suricata-0a0a0a?style=flat-square) ![Zeek](https://img.shields.io/badge/Zeek-0a0a0a?style=flat-square) ![Sigma](https://img.shields.io/badge/Sigma-0a0a0a?style=flat-square) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-0a0a0a?style=flat-square) ![Trivy](https://img.shields.io/badge/Trivy-0a0a0a?style=flat-square&logo=trivy&logoColor=white) ![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-0a0a0a?style=flat-square&logo=zap&logoColor=white) ![cosign](https://img.shields.io/badge/cosign-0a0a0a?style=flat-square) ![gitleaks](https://img.shields.io/badge/gitleaks-0a0a0a?style=flat-square&logo=git&logoColor=white)

**Observability**  
![Prometheus](https://img.shields.io/badge/Prometheus-111111?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-111111?style=flat-square&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-111111?style=flat-square&logo=grafana&logoColor=white) ![Fluent Bit](https://img.shields.io/badge/Fluent%20Bit-111111?style=flat-square&logo=fluentbit&logoColor=white)

**Platforms**  
![Linux](https://img.shields.io/badge/Linux-1a1a1a?style=flat-square&logo=linux&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-1a1a1a?style=flat-square&logo=nginx&logoColor=white)

<a id="stats"></a>
<img src="./assets/h-stats.svg" width="100%" alt="Stats"/>

<div align="center">

<img height="165" src="https://github-stats-extended.vercel.app/api?username=hustlerx01&custom_title=HustlerX&show_icons=true&hide_rank=true&hide_border=false&border_color=2a2a2a&border_radius=0&include_all_commits=true&count_private=true&bg_color=0a0a0a&title_color=ffffff&text_color=bbbbbb&icon_color=ffffff" alt="GitHub stats"/>&nbsp;<img height="165" src="https://streak-stats.demolab.com/?user=hustlerx01&hide_border=false&border=2a2a2a&border_radius=0&background=0a0a0a&stroke=2a2a2a&ring=ffffff&fire=ffffff&currStreakLabel=ffffff&sideNums=eaeaea&currStreakNum=ffffff&dates=888888&sideLabels=bbbbbb" alt="streak"/>

<img width="100%" src="https://raw.githubusercontent.com/hustlerx01/hustlerx01/output/github-contribution-grid-snake-dark.svg" alt="snake eating contributions"/>

</div>

<img src="./assets/quote.svg" width="100%" alt="every alert is a question. good detections answer it before someone has to ask twice."/>

<a id="contact"></a>
<img src="./assets/h-contact.svg" width="100%" alt="Contact"/>

<div align="center">
<table><tr>
<td align="center" width="96"><a href="https://hustlerx.si"><img src="https://api.iconify.design/lucide/globe.svg?color=%23ffffff" width="24" height="24"/><br/><sub><b>website</b></sub></a></td>
<td align="center" width="96"><a href="https://www.linkedin.com/in/hustlerx"><img src="https://api.iconify.design/lucide/linkedin.svg?color=%23ffffff" width="24" height="24"/><br/><sub><b>linkedin</b></sub></a></td>
<td align="center" width="96"><a href="https://github.com/hustlerx01"><img src="https://api.iconify.design/lucide/github.svg?color=%23ffffff" width="24" height="24"/><br/><sub><b>github</b></sub></a></td>
<td align="center" width="96"><a href="mailto:ansarshaikh@hustlerx.si"><img src="https://api.iconify.design/lucide/mail.svg?color=%23ffffff" width="24" height="24"/><br/><sub><b>email</b></sub></a></td>
<td align="center" width="96"><a href="https://discord.com/users/974323061547479120"><img src="https://api.iconify.design/lucide/message-circle.svg?color=%23ffffff" width="24" height="24"/><br/><sub><b>discord</b></sub></a></td>
</tr></table>
</div>


<img src="./assets/footer.svg" width="100%"/>
