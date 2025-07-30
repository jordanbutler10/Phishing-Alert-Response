# 🛡️ Phishing Alert Investigation - SOC1 Analyst Response

## Overview

This project documents a simulated phishing alert investigation conducted as a Level 1 Security Operations Center (SOC) Analyst at a financial services company. The alert involved a suspicious file downloaded by an employee from a phishing email. This README outlines the response steps taken using the official **Phishing Incident Response Playbook** and demonstrates how I handled the incident from detection to escalation.

---

## 📝 Incident Summary

- **Alert Type:** Phishing - Suspicious File Download
- **Alert Severity:** Medium
- **Attachment Type:** Password-protected `.xlsx` spreadsheet
- **Detection Method:** Suspicious file download triggered alert
- **Confirmed Threat:** Yes – Malicious file hash verified via VirusTotal

---

## 🧭 Playbook Steps Followed

### ✅ Step 1: Receive Phishing Alert
The alert was triggered by a suspicious file download. A password-protected spreadsheet attachment was received through email.

### ✅ Step 2: Evaluate the Alert
Investigated the alert metadata, including:
- Sender/Receiver info
- Email content
- File behavior
- File hash analysis

### ✅ Step 3.0: Check for Attachments
The email included a suspicious attachment (confirmed).

### ✅ Step 3.1: Determine if Attachment is Malicious
The file's hash was submitted to **VirusTotal**, which returned a **malicious verdict**.

### ✅ Step 3.2: Escalate the Alert
Per the playbook, confirmed malicious attachments must be escalated. The ticket status was updated to **Escalated**, and Tier 2 SOC personnel were notified.

---

## 🗒️ Ticket Update

- **Ticket Status:** Escalated
- **Comments:**
  > A phishing alert was triggered by a suspicious password-protected spreadsheet. After analyzing the file hash through VirusTotal, the file was confirmed malicious. Per company policy, the ticket has been escalated for further investigation and containment.

---

## 📌 Lessons Learned

- Importance of verifying file hashes using threat intelligence tools.
- Following structured playbooks ensures timely and accurate responses.
- Proper escalation procedures prevent broader compromise.

---

## 🔐 Skills Demonstrated

- Incident evaluation and triage  
- Threat intelligence lookup (hash analysis)  
- Alert escalation and documentation  
- Playbook-driven decision making  
- Professional SOC analyst workflow

---

## 📁 Supporting Files

- `Phishing-incident-response-playbook.docx`: Official playbook used during investigation
- `IncidentHandlerJournal.md`: Personal log (if applicable)
- `AlertTicket_Response.md`: Final alert ticket update summary

---

## ✅ Status

**Complete** – This simulation represents an end-to-end phishing alert investigation and response by a SOC Tier 1 Analyst.

---

## 📫 Contact

**Jordan Butler**  
Cybersecurity Analyst  
[LinkedIn](#) • [GitHub](#) • [Email](mailto:jordanbutler2300@yahoo.com)
