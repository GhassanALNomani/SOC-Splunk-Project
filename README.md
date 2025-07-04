# 🛡️ SOC Lab: Windows Domain with Splunk

This is a home lab project to simulate a basic Security Operations Center (SOC) using Windows infrastructure and Splunk for centralized log collection.

---

## 🧰 Lab Components

| Component           | Description                                 |
|---------------------|---------------------------------------------|
| 🖥️ Domain Controller | Windows Server (Active Directory setup)     |
| 💻 Client Machine    | Windows Server joined to AD domain              |
| ⚙️ Sysmon            | Installed on both DC and client for deep logging |
| 📤 Splunk Universal Forwarder | Installed on both DC and client |
| 📊 Splunk Enterprise | Installed on separate server, used to collect and analyze logs |

---

## 🔄 Log Sources

- Windows Event Logs (Security.evtx)
- Sysmon Logs (Microsoft-Windows-Sysmon/Operational)

---

## 🔌 Log Flow




---

## ✅ Project Status

- ✅ Active Directory setup (Domain: `corp.local`)
- ✅ One Windows 10 client joined to domain
- ✅ Sysmon installed with custom config
- ✅ Splunk Universal Forwarder deployed
- ✅ Splunk Server installed and receiving logs

---

## 🛠️ Next Steps (Coming Soon)

- Add basic detections (e.g., failed login attempts)
- Build Splunk dashboard
- Document sample incident response

---

## 🔗 Author

**Ghassan AlNumani**  
[Portfolio](https://ghassanalnomani.github.io/cybersecurity-portfolio/)
