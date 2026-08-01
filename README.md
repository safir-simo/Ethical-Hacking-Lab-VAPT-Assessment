# 📂 Ethical Hacking Lab – VAPT Assessment

## 📌 Overview
This is a practical ethical hacking assessment performed within a lab. The assessment is conducted using a well-defined penetration testing process consisting of reconnaissance, enumeration, vulnerability assessment, and mitigation processes.

---

## 💾 Tools & Technologies

- Nmap  
- Enum4linux  
- SMBClient  
- Netcat  

---

## 🔍 Assessment Process

The assessment process involves the following steps:

1. **Reconnaissance & Scanning**
   - Network discovery and scanning for open ports
2. **Enumeration**
   - Enumeration of services and users (SMB and FTP)
3. **Vulnerability Discovery**
   - Discovery of insecure configurations and outdated services
4. **Risk Analysis**
   - Likelihood and impact analysis of discovered vulnerabilities
5. **Mitigation**
   - Vulnerability mitigation and verification of mitigations

---

## 🔑 Key Findings

- Anonymous FTP login enabled  
- SMB null session access 
- Outdated Apache Server  
- Telnet service (insecure protocol)  
- Weak system configuration   

---

## 👨🏻‍💻 Mitigation Strategies

- Disabling the anonymous FTP service  
- Restricting guest access for SMB service  
- verified security improvements through reseting 

---

## 🔐 Post Exploitation Concepts

- Persistence through creating user accounts  
- Remote access using Netcat  
- Log monitoring and attacker trace analysis   

---

## 🎯 Objective

To simulate a real-world penetration test and identify security weaknesses in a vulnerable system.

---

## 📄 Assessment Report

📎 The full technical report:
  
[Ethical Hacking Assessment Report](./Ethical-Hacking-Report.pdf)

---

## ⚠️ Disclaimer

This project was done in a lab environment. No real systems were harmed during this project.
