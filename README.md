# 🛡️ ShadowFox Cybersecurity Internship — Lab Report

## ⚠️ Disclaimer
This report is based on **authorized lab environments and simulated targets only**. No real client data, systems, or credentials are disclosed. All activities were performed in a controlled, legal, and ethical lab setting for educational purposes.

---

## 📋 Internship Details

| Field | Detail |
|---|---|
| **Company** | ShadowFox |
| **Domain** | Cybersecurity |
| **Level** | Beginner – Advanced |
| **Duration** | 1 Month |

---

## 🧰 Tools Used

- Nmap
- Gobuster
- Wireshark
- Metasploit
- VeraCrypt
- enum4linux
- Hydra

---

## 🔍 Task 1: Port Scanning

- **Objective:** Identify open ports and running services on the target
- **Tool:** Nmap
- **Result:** HTTP service detected
- **Risk Level:** 🟢 Low
- **Mitigation:** Enforce HTTPS, apply regular patching

---

## 📂 Task 2: Directory Enumeration

- **Tool:** Gobuster
- **Finding:** Sensitive directories exposed on the web server
- **Risk Level:** 🟡 Medium
- **Mitigation:** Implement access controls, remove exposed repo/config files

---

## 🔑 Task 3: Credential Exposure (Lab)

- **Observation:** Credentials transmitted in plaintext over the network
- **Risk Level:** 🔴 High
- **Mitigation:** Enforce HTTPS, enable HSTS, implement MFA

---

## 🧪 Intermediate & Advanced Tasks

- Reverse shell (lab simulation)
- Disk decryption (VeraCrypt)
- Privilege escalation (TryHackMe lab)

---

## 🎓 Key Learnings

- SOC investigation workflow
- Vulnerability documentation practices
- Risk scoring using CVSS
- Incident mitigation strategies

---

## 📌 Note

All findings, tools, and techniques documented here were applied strictly within **authorized, isolated lab environments** (e.g., TryHackMe) for skill development purposes and do not reflect any unauthorized testing of live systems.
