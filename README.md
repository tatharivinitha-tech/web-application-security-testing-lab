web-application-security-testing-lab


The Web Application Security Testing Lab is a comprehensive, hands-on cybersecurity environment designed to simulate real-world attack and defense scenarios for web applications.
This project integrates offensive security testing, threat analysis, and defensive remediation in a containerized, reproducible architecture built with Kali Linux, Docker, and Proxmox.

It demonstrates end-to-end web penetration testing workflows aligned with the OWASP Web Security Testing Guide (WSTG), focusing on vulnerability discovery, CVSS scoring, and secure patch verification.

🔍 Key Features
	•	OWASP-Compliant Testing Framework – Coverage across injection flaws, broken authentication, XSS, security misconfigurations, and more.
	•	Multi-Tool Integration – Combines Burp Suite, OWASP ZAP, Nmap, SQLMap, and Splunk for hybrid automated/manual testing pipelines.
	•	Realistic Vulnerable Targets – Includes DVWA, OWASP Juice Shop, and custom PHP applications hosted on isolated Docker containers.
	•	CVSS v3.1 Risk Assessment – Quantitative scoring of vulnerabilities with mapped severity and business impact.
	•	Remediation Validation – Secure code reviews and retesting after implementing fixes such as parameterized queries, CSP headers, and input sanitization.
	•	Evidence Repository – Structured proof-of-concept (PoC) screenshots, logs, and reports demonstrating exploit execution and verification.
	•	Scalable Cloud-Lab Architecture – Deployable in Proxmox, VirtualBox, or AWS EC2 environments for academic or professional demonstrations.

🧩 Architecture Overview
┌────────────────────────┐
│  Host (Proxmox Hypervisor) │
└──────────┬────────────┘
           │
┌──────────┴────────────┐
│  Kali Linux (Attacker VM) │
│  Tools: ZAP, Burp, Nmap, SQLMap, Splunk │
└──────────┬────────────┘
           │
┌──────────┴────────────┐
│ Dockerized Targets (DVWA, Juice Shop) │
│ Simulated Web App + DB vulnerabilities │
└────────────────────────┘


⸻

🧾 Reporting & Deliverables
	•	Detailed penetration testing report (/report/Final_Project_Report-WebAppSecurityTesting.pdf)
	•	Evidence folder (/evidence/) with PoC screenshots and tool outputs
	•	Secure coding recommendations and retest results (/patches/)
	•	README-guided reproduction steps for researchers and students

⸻

🔐 Learning Outcomes
	•	End-to-end mastery of OWASP Top 10 testing in real-world conditions
	•	Familiarity with offensive security tools and CVSS scoring
	•	Experience building isolated and reproducible test environments
	•	Understanding of defensive security practices and validation testing

