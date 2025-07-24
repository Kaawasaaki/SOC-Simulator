#  SOC Simulator Lab (TryHackMe) — Phishing Detection and Alert Triage using Splunk

This repository documents my hands-on experience in a simulated Security Operations Center (SOC) environment, completed via the **TryHackMe: SOC Level 1 - Simulator Lab**. The goal was to analyze real-time alerts in Splunk, identify phishing attempts, classify events, and escalate incidents according to severity and confidence.

---

##  Project Overview

- **Platform**: TryHackMe - SOC Level 1 (SOC Simulator)
- **Tool Used**: Splunk
- **Focus Areas**: Email Phishing Analysis, URL Threat Detection, Firewall Log Analysis, Alert Classification
- **Scenario**: Detect, investigate, and respond to a series of suspicious emails and network traffic using real logs and alerts generated in a simulated SOC.

---

## Key Highlights

| Metric                          | Result           |
|-------------------------------|------------------|
|  True Positive Identification Rate | **100%**          |
| False Positive Identification Rate | **100%**          |
|  Total Alerts Investigated    | 4 alerts         |
|  Mean Time to Resolve         | 5 minutes        |
| ⏱ Mean Dwell Time              | 13 minutes       |

---

##  Included Artifacts

-  Screenshots of Splunk Dashboard
- Alert logs from the simulation
-  Sample JSON event data
-  Annotated phishing indicators
-  Incident classification summary

---

## Skills Demonstrated

- Log analysis and filtering in Splunk
-  Email header and URL investigation
-  Correlating alerts to identify attack vectors
- Applying playbooks for triage and escalation
-  Classification of alerts into:
  - **True Positive**
  - **False Positive**
-  Writing concise incident reports with evidence

---

## Relevance to Blue Team Roles

This lab closely mirrors real-world Tier 1 SOC workflows including:

- Email phishing triage
- Threat intel matching (blacklists, URL shorteners)
- Alert enrichment and prioritization
- Splunk dashboard usage for detection & response


