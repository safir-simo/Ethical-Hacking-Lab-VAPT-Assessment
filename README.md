# 📂 Ethical Hacking Lab – VAPT Assessment

## 📌 Overview
This is a practical ethical hacking assessment performed within a lab. The assessment is conducted using a well-defined penetration testing process consisting of reconnaissance, enumeration, vulnerability assessment, and mitigation processes.

---

## 💾 Tools & Technologies

- Nmap   
- Enum4linux  
- SMBClient  
- Netcat
- Metaspliot
- Kali Linux   

---

## 🔍 Assessment Process

The assessment process involves the following steps:

1. **Reconnaissance & Scanning**
   - Network discovery and scanning for open ports
   - information gathering
2. **Enumeration**
   - Enumeration of services and users (SMB and FTP)
   - Port scanning
   - Service Version detection
3. **Vulnerability Discovery**
   - Discovery of insecure configurations and outdated services
   - Mapping attack vectors
4. **Exploitation**
   - Likelihood and impact analysis of discovered vulnerabilities
   - Gaining access using discovered vulnerabilities 
5. **Post-Exploration**
   - Privilege escalation
   - impact analysis
6. **Reporting**
   - Documenting Findings
   - Providing remediation recommendations      

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

## 📚 Skill Demonstrated

- Ethical Hacking & Penetration Testing
- Vulnerability Analysis
- Security tools Usage
- Technical Reporting
- Critical Thinking & Problem Solving 


---

## 🎯 Objective

To simulate a real-world penetration test and identify security weaknesses in a vulnerable system.

---

## 📄 Assessment Report

A detailed assessment report is included, covering:
- Vulnerability descriptions
- Proof of concept (PoC)
- Risk rating
- Mitigation strategies

📎 Full technical report:
  
[Ethical Hacking Assessment Report](./Ethical-Hacking-Report.pdf)

---

## ⚠️ Disclaimer

This project was done in a lab environment. No real systems were harmed during this project.
