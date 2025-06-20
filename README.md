# 👁️ SIEM Home Lab

## 🔍 Overview

This lab simulates a real-world security monitoring environment using **Azure Sentinel** and a honeypot virtual machine. The objective was to practice detecting, logging, and analyzing unauthorized access attempts (specifically brute-force RDP attacks) in a cloud-hosted setup. Data from the honeypot is visualized and enriched with attacker geolocation using custom PowerShell scripting.

---

## 🛠️ Tools & Technologies

- **SIEM Platform:** Azure Sentinel
- **Log Source:** Windows 10 VM acting as a honeypot
- **Scripting Language:** PowerShell (for geolocation enrichment)
- **Cloud Environment:** Microsoft Azure

---

## 📌 Objectives Achieved

- ✅ Deployed and configured a honeypot virtual machine on Azure  
- ✅ Connected the VM to Azure Sentinel for live event monitoring  
- ✅ Captured and analyzed RDP brute-force attempts from external IPs  
- ✅ Used PowerShell to retrieve geolocation data for attacker IPs  
- ✅ Mapped attack sources using Azure Sentinel’s built-in visualization tools  

---

## 🧠 Skills Demonstrated

- Cloud-based SIEM configuration  
- Real-time log ingestion and analysis  
- Threat detection and log correlation  
- PowerShell scripting for data enrichment  
- SOC-level event monitoring workflows  
