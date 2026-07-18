# 🛡️ SOC Internship Project – pfSense & Wazuh Integration

## 📌 Project Overview

This project was completed as part of my **SOC Analyst Internship**. The objective was to build a Security Operations Center (SOC) lab using **pfSense Firewall**, **Ubuntu SOC Server**, **Syslog-ng**, and **Wazuh SIEM** to centralize firewall logs and monitor security events.

The project provided practical experience with firewall configuration, Linux administration, centralized logging, SIEM deployment, and troubleshooting.

---

## 🎯 Objectives

- Configure pfSense Firewall
- Set up WAN, LAN, and OPT1 interfaces
- Configure Remote Syslog
- Install and configure Syslog-ng
- Receive firewall logs on Ubuntu
- Deploy Wazuh SIEM
- Install and register the Wazuh Agent
- Monitor logs through the Wazuh Dashboard
- Verify communication between all systems

---

## 🛠 Technologies Used

- VMware Workstation
- pfSense Firewall
- Ubuntu Server
- Wazuh SIEM
- Wazuh Agent
- Syslog-ng
- Squid Proxy
- ClamAV
- Kali Linux

---

## 🏗️ Lab Architecture

```text
Internet
    │
    ▼
pfSense Firewall
    │
Remote Syslog
    ▼
Ubuntu SOC Server
 (Syslog-ng)
    │
Wazuh Agent
    ▼
Wazuh Manager
    ▼
Wazuh Dashboard
```

---

## ✅ Implementation Summary

- Configured pfSense firewall interfaces.
- Enabled Remote Syslog on pfSense.
- Installed and configured Syslog-ng on Ubuntu.
- Verified firewall logs were received in `/var/log/pfsense.log`.
- Deployed the Wazuh platform.
- Installed and registered the Ubuntu Wazuh Agent.
- Configured Wazuh Logcollector to monitor pfSense log files.
- Tested connectivity and verified centralized log collection.
- Performed troubleshooting to resolve networking and service issues.

---

## 📂 Repository Structure

```text
pfSense-Wazuh-Integration
│
├── README.md
├── Report/
├── Screenshots/
├── Configuration/
└── Commands/
```

---

## 📸 Project Screenshots

Screenshots included:

- VMware Lab Environment
- pfSense Dashboard
- Network Configuration
- Remote Syslog Configuration
- Ubuntu Receiving Logs
- Wazuh Dashboard
- Active Wazuh Agents
- Final Verification

---

## 📚 Skills Gained

- Firewall Configuration
- SIEM Deployment
- Linux Administration
- Centralized Logging
- Network Security
- Log Analysis
- VMware Virtualization
- Troubleshooting
- Security Monitoring

---

## 📖 Conclusion

This project helped me understand how firewall logs can be collected, centralized, and monitored in a SOC environment. It strengthened my practical knowledge of Linux, networking, SIEM, and security monitoring while improving my troubleshooting skills.

---

## 👨‍💻 Author

**Abdullah Masood**

BS Cyber Security Student

SOC Analyst Intern
