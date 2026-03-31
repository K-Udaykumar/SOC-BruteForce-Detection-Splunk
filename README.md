# 🔐 SOC Brute Force Detection using Splunk

## 📌 Project Overview

This project demonstrates detection of brute-force login attacks using Splunk SIEM. It simulates an attacker attempting unauthorized access and shows how logs are collected, analyzed, and monitored in a SOC environment.

---

## 🏗 Architecture

![Architecture](architecture/soc_bruteforce_architecture.png)

---

## 📥 Data Collection

Logs are collected from the Windows system using Splunk Universal Forwarder.

![Forwarder Monitoring](screenshots/01_data_collection/forwarder_monitoring.png)
![Forwarding Status](screenshots/01_data_collection/forwarding_status.png)

---

## 📊 Log Ingestion

Windows Security logs (Event ID 4625) are ingested into Splunk.

![Logs Ingested](screenshots/02_log_ingestion/logs_ingested.png)

---

## 🚨 Detection

Brute-force login attempts are detected using Splunk queries.

![Detection Query](screenshots/03_detection/detection_query.png)
![Alert Triggered](screenshots/03_detection/alert_triggered.png)

---

## 📈 Visualization

A dashboard is created to monitor failed login attempts.

![Dashboard](screenshots/04_visualization/dashboard.png)

---

## 🛠 Troubleshooting

### ❌ No Results Issue

Search returned no results due to incorrect time range or missing data.
![No Results](troubleshooting/01_no_results_issue.png)

---

### ❌ Forwarder Log Error

Forwarder encountered log access or configuration issues.
![Forwarder Error](troubleshooting/02_forwarder_log_error.png)

---

### ❌ No Events Found

No logs were ingested due to misconfiguration.
![No Events](troubleshooting/03_no_events_found.png)

---

## ⚙️ Technologies Used

* Splunk Enterprise
* Splunk Universal Forwarder
* Windows Event Logs
* Kali Linux (Attack Simulation)

---

## 🎯 Outcome

* Simulated brute-force attack successfully
* Detected failed login attempts (Event ID 4625)
* Created alerts for monitoring
* Built dashboard for visualization
* Demonstrated SOC workflow from detection to response
