🛡️ SOC L1 Playbook – Phishing Detection

This repository contains a SOC Level 1 (L1) Analyst Playbook for detecting and responding to phishing emails.
It provides structured guidance, tools, and workflows to help analysts quickly identify, validate, and mitigate phishing threats.

📌 Overview

Phishing is one of the most common attack vectors used by threat actors to steal credentials, deliver malware, and gain unauthorized access.
This playbook equips SOC L1 analysts with:

Practical detection techniques

IOC (Indicator of Compromise) analysis methods

Tool references (VirusTotal, MXToolbox, WHOIS, URLScan)

A step-by-step incident handling checklist

📖 Contents

Phishing Basics – what phishing is, attacker goals, and risks

Mitigation Strategies – MFA, SPF/DKIM/DMARC, user training

Email Authentication Protocols – SPF, DKIM, DMARC explained

IOC Analysis Tools – VirusTotal, URLScan, MXToolbox, WHOIS

Sample Phishing Email – with extracted IOCs and analysis

SOC Analyst Checklist – step-by-step workflow

IOC Handling Guide – actions for suspicious indicators

Supplementary Analysis – WHOIS/MXToolbox checks

SOC L1 Handling Guidelines – when to block, escalate, or close

🔎 Workflow (Simplified)

Analyze headers → Compare Return-Path, From, Reply-To

Check SPF/DKIM/DMARC → Validate authenticity

Inspect URLs/domains → Run in VirusTotal/URLScan

Check domain reputation → WHOIS & MXToolbox

Classify:

✅ Clean → Document & close

⚠️ Suspicious → Escalate to L2 with evidence

🚨 Malicious → Block, add IOCs to SIEM, alert users

🛠️ Tools Referenced

VirusTotal
 – File/URL/domain reputation

URLScan.io
 – Dynamic sandbox URL analysis

MXToolbox
 – DNS, MX, SPF, DKIM, DMARC checks

WHOIS Lookup
 – Domain registration info

📑 Usage

This playbook can be used by:

SOC L1 Analysts – as a first-response guide

Security Teams – for training & onboarding

Organizations – to standardize phishing triage procedures

🚀 Future Improvements

 Add flowchart for quick triage decisions

 Add severity levels & SLAs (response timelines)

 Add reporting template for consistent documentation

👨‍💻 Author

Created by Lovish Ramphul (2025)

If you find this useful, feel free to ⭐ star the repo and contribute improvements!
