# LogAnalysis-ThreatDetection
Step-by-step collecting, parsing, and analyzing log data to identify potential security threats.

This project demonstrates basic log analysis and threat detection techniques using open-source tools and real system log data. The goal is to simulate a basic Security Operations Center (SOC) process by collecting logs, identifying suspicious activity, and documenting the investigation process.

---

## 📌 Objectives

- Collect system and application logs from a Linux virtual machine.
- Set up a log analysis tool (Splunk or ELK Stack).
- Parse and analyze logs to detect suspicious or malicious behavior.
- Document identified threats and explain the logic behind detection rules.
- (Optional) Automate basic detection tasks using Python.

---

## 🧰 Tools & Technologies

- **Operating System:** Ubuntu (Oracle Cloud VM)
- **Log Sources:** 
  - `/var/log/auth.log`
  - `/var/log/syslog` or `/var/log/messages`
  - `/var/log/apache2/access.log` (optional)
- **Log Analysis Tool:** Splunk Free or ELK Stack (Elasticsearch, Logstash, Kibana)
- **Scripting Language:** Python (for optional automation)
- **Other Tools:** Filebeat, Fail2Ban, UFW/IPTables

---

## 🏗️ Project Structure
