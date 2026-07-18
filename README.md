# 🛡️ SOC Internship Week 3 – pfSense, Squid Proxy & Wazuh SIEM Lab
![pfSense](https://img.shields.io/badge/pfSense-2.8.1-blue)

![Wazuh](https://img.shields.io/badge/Wazuh-4.14.6-green)

![Platform](https://img.shields.io/badge/Platform-VirtualBox-orange)

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

![License](https://img.shields.io/badge/License-MIT-blue)
## 📖 Project Overview

This project was completed as part of my SOC Internship at ITSimplera Solutions.

The objective was to build a complete security monitoring environment capable of:

- Filtering network traffic using pfSense Firewall
- Inspecting web traffic using Squid Proxy
- Detecting malware using SquidClamAV
- Forwarding firewall logs to Wazuh SIEM
- Creating custom Wazuh detection rules
- Monitoring security alerts from the Wazuh Dashboard

---

# 🏗️ Lab Architecture

```
                 Internet
                     │
                     │
              pfSense Firewall
                     │
        ┌────────────┴────────────┐
        │                         │
   Parrot OS                 Wazuh Server
 (Client Machine)              (SIEM)
```

---

## 🌐 Network Configuration

| Device | IP Address |
|--------|------------|
| pfSense LAN | 192.168.1.1 |
| Parrot OS | 192.168.1.100 |
| Wazuh Server | 192.168.1.101 |
---

# 🌐 Network Configuration

| Device | IP Address |
|----------|-------------|
| pfSense LAN | 192.168.1.1 |
| Parrot OS | 192.168.1.100 |
| Wazuh Server | 192.168.1.101 |

---

# 🚀 Project Workflow

1. Deploy pfSense Firewall
2. Configure Squid Proxy
3. Enable SquidClamAV
4. Configure Remote Syslog
5. Deploy Wazuh SIEM
6. Create Custom Detection Rule
7. Generate ICMP Traffic
8. Download EICAR Test File
9. Monitor Alerts in Wazuh Dashboard

---

# ✅ Testing Performed

✔ Firewall Traffic Monitoring

✔ DNSBL Website Blocking

✔ Malware Detection using EICAR

✔ Syslog Log Forwarding

✔ Wazuh Log Collection

✔ Custom Rule Validation

✔ Dashboard Alert Verification

---
## 🏆 Key Achievements

- Successfully deployed pfSense Firewall
- Configured Squid Proxy
- Integrated SquidClamAV for malware scanning
- Forwarded pfSense logs to Wazuh using Syslog
- Created a custom Wazuh detection rule
- Detected and blocked the EICAR malware test file
- Verified alert generation in the Wazuh Dashboard
  
# 📸 Project Screenshots

All screenshots are available in the **Images** folder.

They include:

- Virtual Lab
- Network Topology
- pfSense Dashboard
- DNSBL Blocking
- SquidClamAV Malware Detection
- Firewall Logs
- Wazuh Dashboard
- Custom Rule
- Alert Generation

---

## 📄 Project Report

The complete internship report is available inside the **Report** folder.

---

# 🎯 Skills Demonstrated

- Network Security
- Firewall Administration
- Proxy Server Configuration
- Malware Detection
- Security Monitoring
- SIEM Administration
- Wazuh Rule Creation
- Syslog Configuration
- Incident Response
- Blue Team Operations

## 📁 Repository Structure

```text
pfSense-Squid-Wazuh-SOC-Lab/
├── Images/
│   ├── image1.png
│   ├── image2.png
│   ├── image3.png
│   └── ...
│
├── Report/
│   ├── SOC_Internship_Week3_Report.pdf
│   └── README.md
│
├── LICENSE
└── README.md
```

---

# 📚 References

- Wazuh Documentation
- Netgate pfSense Documentation
- Squid Proxy Documentation
- ClamAV Documentation
- EICAR Test File

---
---

## 🚀 Future Improvements

- Integrate Suricata IDS/IPS
- Add Windows and Linux Wazuh Agents
- Monitor Sysmon Events
- Configure Email Alerts
- Integrate Threat Intelligence Feeds

## 📄 Project Report
The complete internship report is available in the **Report** folder.
**File:** `Report/SOC_Internship_Week3_Report.pdf`

## 👨‍💻 Author

**Huzaifa Saeed**

SOC Intern

ITSimplera Solutions
