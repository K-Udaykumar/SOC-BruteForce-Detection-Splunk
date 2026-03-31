# 🔐 SOC Brute Force Detection using Splunk

## 📌 Project Overview

This project demonstrates detection of brute-force login attacks using Splunk SIEM.

---

## 🏗 Architecture

![Architecture](architecture/architecture.png)

---

## 📥 Data Collection

![Forwarder Monitoring](screenshots/01_data_collection/forwarder_monitoring.png)
![Forwarding Status](screenshots/01_data_collection/forwarding_status.png)

---

## 📊 Log Ingestion

![Logs Ingested](screenshots/02_log_ingestion/logs_ingested.png)

---

## 🚨 Detection

![Detection Query](screenshots/03_detection/detection_query.png)
![Alert Triggered](screenshots/03_detection/alert_triggered.png)

---

## 📈 Visualization

![Dashboard](screenshots/04_visualization/dashboard.png)

---

## 🛠 Troubleshooting

### ❌ No Results Issue

![No Results](troubleshooting/no_results_issue.png)

### ❌ Forwarder Log Error

![Forwarder Error](troubleshooting/forwarder_log_error.png)

### ❌ No Events Found

![No Events](troubleshooting/no_events_found.png)

---

## ⚙️ Technologies Used

* Splunk Enterprise
* Splunk Universal Forwarder
* Windows Event Logs
* Kali Linux

---

## 🎯 Outcome

* Detected brute-force attacks
* Built alert system
* Created SOC-style dashboard
