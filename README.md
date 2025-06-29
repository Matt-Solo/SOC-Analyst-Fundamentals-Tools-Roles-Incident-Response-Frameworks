# SOC-Analyst-Fundamentals-Tools-Roles-Incident-Response-Frameworks


This project outlines the core structure and operations of a Security Operations Center (SOC). It covers technologies like SIEM, EDR, TIP, and SOAR, analyst roles (L1–L3), and incident response frameworks (NIST and SANS). Ideal for SOC Analyst beginners and cybersecurity learners building foundational knowledge.


---

## 📘 What is a SOC?

A **Security Operations Center (SOC)** is a centralized team within an organization responsible for continuously monitoring, detecting, analyzing, and responding to cybersecurity threats in real-time.

- 🔍 Threat Monitoring  
- 🚨 Investigating Alerts  
- 🛡️ Responding to Incidents  

---

## 🛠️ Core SOC Technologies & Tools

| Tool/Platform | Description |
|---------------|-------------|
| **SIEM** (Security Information and Event Management) | Combines SIM + SEM to collect and analyze log data from multiple sources to detect threats. |
| **EDR** (Endpoint Detection and Response) | Detects and investigates suspicious activities on endpoints (e.g., laptops, servers) with real-time response. |
| **TIP** (Threat Intelligence Platform) | Centralizes and automates the collection of external threat intelligence feeds to support proactive defense. |
| **SOAR** (Security Orchestration, Automation and Response) | Integrates SOC tools and automates alert triage, investigation, and response workflows. |
| **Ticketing Systems** | Used to track security incidents and manage analyst workflows (e.g., Jira, ServiceNow). |
| **MDR** (Managed Detection and Response) | Outsourced security service that provides 24/7 threat monitoring and incident response. |

---

##  SOC Analyst Roles

### L1 SOC Analyst (Tier 1)

> **Definition:** Entry-level analysts who monitor alerts, perform initial triage, and escalate suspicious activity.

- ✅ Alert triage  
- 🔍 Basic investigation  
- 🧠 First line of defense  
- 🔎 Identify anomalies  
- 📥 Raise whitelist requests  

---

### L2 SOC Analyst (Tier 2)

> **Definition:** Experienced analysts who perform deeper investigations, respond to incidents, and handle escalations.

- 🧪 Deep-dive investigations  
- 🔁 Handle escalated alerts  
- ✅ Approve whitelist requests  
- 📊 Create detection rules  
- 🧑‍🏫 Mentor junior analysts  

---

### L3 SOC Analyst (Tier 3)

> **Definition:** Senior analysts responsible for threat hunting, managing incidents, and designing SOC strategies.

- 🧑‍🤝‍🧑 Client onboarding  
- 🧾 Documentation and reporting  
- 🔧 Incident management  
- 📢 Technical stakeholder communication  
- 📦 SOAR playbook design  

---

## ⚙️ SIEM Overview

> **SIEM** combines SIM (Security Information Management) and SEM (Security Event Management) into a unified platform for log-based threat detection and response.

### 🔍 SIEM Features

- 📥 Log collection & aggregation  
- 🔍 Parsing & normalization  
- 🧠 Enrichment & AI-based detection  
- 📦 Indexing & storage  
- 🚨 Rule-based alerting  
- 📊 Dashboards for visibility  

---

## 💻 EDR Overview

> **EDR (Endpoint Detection and Response)** provides continuous monitoring and real-time response capabilities for endpoint devices. It focuses on system-level behavior rather than network-wide logs.

### 🔎 EDR Functions

- 📡 Real-time endpoint monitoring  
- 📁 Collects detailed endpoint activity  
- 🚫 Signature-less threat detection  
- ⚙️ Automated rule-based responses  

### 🔧 EDR Collects

- Network connections  
- Process execution  
- Registry modifications  
- Currently running processes  
- Cross-process interactions  

### 🏗️ EDR Architecture

[ Endpoint Device ] ⇄ [ EDR Server ] ⇄ [ Threat Intelligence Platform ]



---

## 📚 Incident Response Frameworks

### 🔐 NIST Incident Response Framework

> A U.S. government standard framework used by many enterprises for structured incident response.

1. **Preparation** – Define tools, roles, and communication plans  
2. **Detection & Analysis** – Identify and confirm incidents  
3. **Containment, Eradication, Recovery** – Stop the attack, remove it, and restore systems  
4. **Post-Incident Activity** – Lessons learned, documentation, and process improvement  

---

### 🧰 SANS Incident Response Framework

> A widely adopted practical framework for security incident handling, developed by the SANS Institute.

1. **Preparation**  
2. **Identification**  
3. **Containment**  
4. **Eradication**  
5. **Recovery**  

---

## 🚀 Next Steps

As part of my ongoing learning and hands-on development as an **aspiring SOC Analyst**, I will be working on the following projects in the coming weeks:

- 🏗️ **Build a SIEM Lab**  
  Set up a log monitoring environment using ELK Stack or Splunk to collect, parse, and visualize security events.

- 📜 **Document Alert Rules & Investigations**  
  Create detection rules for common threats, triage alerts, and document findings with investigation reports.

- 🤖 **Develop SOAR Playbooks**  
  Use TheHive & Cortex to automate alert triage and response workflows, integrating with external threat intel sources.

Stay tuned as I update this repository with detailed steps, screenshots, scripts, and documentation for each project.




