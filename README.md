 
# 🛡️ SOC Threat Detection & Investigation using Splunk

This project simulates a mini-SOC environment using **Splunk** to ingest logs, detect malicious activity, trigger alerts, and conduct incident investigations. It demonstrates core skills of a SOC analyst such as detection engineering, threat hunting, and response documentation.

---

## 📂 Project Structure

SOC-Splunk-Project/
├── logs/ # Sample logs (Windows, Linux, Firewall, Web)
├── detections/ # Saved Splunk detection queries
├── alerts/ # Simulated alerts from Splunk
├── incident_reports/ # Markdown files with full incident analysis
├── dashboards/ # Splunk JSON dashboard exports
└── README.md # Project documentation

---

## 🧪 Simulated Use Cases

| Incident ID | Detection Use Case               | MITRE Tactic      | Technique         |
|-------------|----------------------------------|-------------------|-------------------|
| 001         | Brute Force Login (SSH/RDP)      | Initial Access    | T1110             |
| 002         | Suspicious PowerShell Execution  | Execution         | T1059             |
| 003         | Data Exfiltration via HTTP       | Exfiltration      | T1048             |

---

## 🧰 Tools & Technologies

- **Splunk Free / Enterprise Trial**
- **Sample Logs** (Sysmon, Linux `auth.log`, Apache, Firewall)
- **MITRE ATT&CK Navigator**
- **Windows Event Logs**, **Web Logs**, **Firewall Logs**
- Optional: Suricata, Wireshark for log generation

---

## 📊 Features

- Detection Engineering with SPL (Splunk Processing Language)
- SOC Dashboard with metrics and visualizations
- Simulated alerts and responses
- Incident reports with ATT&CK mapping and remediation

---

## 📎 Link

🔗 [Project Portfolio Link](https://ghassanalnomani.github.io/cybersecurity-portfolio/)  
🔗 [View on GitHub](https://github.com/ghassanalnomani/SOC-Splunk-Project)

---

## 📌 Status

✅ Project Structure Created  
🛠️ Detection Rules and Incident Reports: In Progress  
📈 Dashboard Visualization: Coming Soon