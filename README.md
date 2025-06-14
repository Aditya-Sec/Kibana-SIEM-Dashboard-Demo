# Kibana-SIEM-Dashboard-Demo
Detect brute force login attacks using Kibana with sample Linux logs.

# 📊 Kibana SIEM Dashboard – Brute Force Attack Detection

This project demonstrates a mini-SOC (Security Operations Center) use case using the ELK stack (Elasticsearch, Logstash, Kibana). It showcases how to detect brute force login attacks using simulated Linux authentication logs and visualize them in Kibana.

---

## 🎯 Project Purpose

To simulate real-world brute force attacks and build a dashboard that detects login anomalies such as:
- Repeated failed login attempts
- Suspicious IP addresses
- Geolocation-based login insights

---

## 🛠 Tools & Stack

- **Kibana** – Log visualization and dashboarding
- **Elasticsearch** – Indexing and searching log data
- **Sample Linux Logs** – Simulated `/var/log/auth.log` format
- *(Optional)* Filebeat/Logstash for ingestion

---

## 📁 Log Data

File: `sample-logs/linux-auth-failed.csv`

Example data:
```csv
timestamp,username,ip_address,status
2025-06-10 10:22:01,root,192.168.1.10,Failed
2025-06-10 10:23:45,admin,185.23.121.55,Failed
2025-06-10 10:24:12,admin,185.23.121.55,Failed
2025-06-10 10:25:00,admin,185.23.121.55,Failed
2025-06-10 10:25:22,user1,182.45.17.101,Failed
2025-06-10 10:25:49,user1,182.45.17.101,Failed
