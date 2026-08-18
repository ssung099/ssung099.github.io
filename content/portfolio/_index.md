---
title: Security Portfolio
---

Security-focused work spanning offensive testing, vulnerability research, and personal projects.

<!-- ## tiny-dec — RISC-V Decompiler Research

Ongoing research project building a 19-stage RV32I-to-C decompiler pipeline with a Ghidra-inspired p-code IR, documented as a public blog series to better understand the black box of a decompiler.

**Skills:** binary lifting, IR design, control-flow recovery, compiler theory, technical writing

**Link:** [Blog series](https://ssung.xyz) -->

## SOC Triage Shift — Cloudora Alert Queue

Ran a full alert triage queue for a fictional client — 12 alerts across identity, endpoint, network, and email — each worked to a defensible verdict with severity and action.

**Result:** 2 true positives, 1 escalation, 7 false positives (root-caused), 1 held pending evidence, 1 duplicate closed

**Skills:** alert triage methodology, hypothesis-driven investigation, log/context correlation, severity scoring, ServiceNow ticketing, MITRE ATT&CK mapping

**Link:** [GitHub](https://github.com/ssung099/cloudora-triage-shift)

## Incident Response — Payroll Phishing Campaign

Investigated a simulated payroll-themed credential phishing campaign for a fictional client — spearphishing → credential harvesting → account takeover — from detection through containment.

**Skills:** KQL threat hunting (Microsoft Sentinel / Azure Data Explorer), email authentication analysis (SPF/DKIM/DMARC), phishing triage, MITRE ATT&CK mapping, incident reporting

**MITRE ATT&CK:** T1566.002, T1598.003, T1078.004

**Link:** [GitHub](https://github.com/ssung099/cloudora-payroll-phishing-investigation)

## Incident Response — Executive Account Takeover

Investigated a simulated executive account takeover for a fictional client — password spray → account compromise → MFA persistence → BEC staging — from detection through containment.

**Skills:** KQL threat hunting (Microsoft Sentinel / Azure Data Explorer), sign-in log analysis, MITRE ATT&CK mapping, incident reporting

**MITRE ATT&CK:** T1110.003, T1078, T1098.005, T1564.008

**Link:** [GitHub](https://github.com/ssung099/cloudora-executive-ato-investigation)

## IoT Security Assessment — Hydroficient

Assessed and hardened an MQTT-based IoT device pipeline for a fictional hotel client, from transport security through anomaly detection.

**Skills:** mTLS / certificate-based device auth, replay-attack defense, TLS performance benchmarking, anomaly detection (Isolation Forest), security assessment reporting

**Link:** [Github](https://github.com/ssung099/hydroficient-iot-externship)

## Vulnerability Research Labs

Reproduced and root-caused real-world CVEs end-to-end, from crash to exploit to patch analysis. 

**Covers:** CVE-2026-4946 (Ghidra RCE), CVE-2014-6271 (Shellshock), CVE-2022-42889 (Text4Shell)

**Skills:** vulnerability analysis, exploit development, patch diffing, reverse engineering

**Link:** [Github](https://github.com/ssung099/Vulnerability-Labs)

## CVE Notifier

A Discord bot that syncs the full NVD database and polls it for new/updated CVEs, posting real-time alerts with a `/cve` lookup command.

**Skills:** API integration, database sync/polling architecture, bot development

**Link:** [GitHub](https://github.com/ssung099/cve-notifier)