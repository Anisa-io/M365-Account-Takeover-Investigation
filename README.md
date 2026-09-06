# ☁️ M365 Account Takeover Investigation

This repository contains a professional Tier-1 SOC incident investigation of a simulated multi-stage cloud attack against a Microsoft 365 environment. 

## 🚨 Overview
By analyzing raw JSON telemetry from Microsoft Entra ID (Sign-in Logs) and Exchange Online (Audit Logs), I identified and documented a complete attack chain:
1. **MFA Fatigue / Push Bombing** leading to initial access.
2. **Session Token Hijacking** (MFA bypass via stolen session token).
3. **Malicious Inbox Forwarding Rule** (Business Email Compromise persistence).

## 📂 Repository Contents
*   [`Incident-Response-Report.md`](./Incident-Response-Report.md) — The full Tier-1 investigation, timeline, IOCs, and remediation ticket.

## 🛠️ Core Competencies Demonstrated
*   Cloud Identity Triage (Microsoft Entra ID)
*   Raw JSON Log Analysis
*   M365 Unified Audit Log Hunting
*   Incident Escalation & Remediation Planning
*   Threat Actor TTP Identification (MITRE ATT&CK: T1621, T1539, T1114.003)
