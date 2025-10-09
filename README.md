# sre-upskilling-labs
Hands-on projects for SRE/App Support upskilling — automation, monitoring, and cloud

### 🔹 PowerShell Script – Service Health Check & Auto-Restart

* **Problem:** Services in production sometimes stop unexpectedly, impacting users.
* **Solution:** A PowerShell script that checks the status of critical Windows services and automatically restarts them if stopped.
* **Value:** Reduces downtime, ensures services are always running.

---

### 🔹 PowerShell Script – Log File Backup Automation

* **Problem:** Manual log file backups take time and risk human error.
* **Solution:** Script automates log file archiving and moves them to a backup folder with timestamps.
* **Value:** Saves admin effort and keeps logs organized for troubleshooting.

---

### 🔹 Python Script – Log Parser

* **Problem:** Identifying errors in huge log files is difficult.
* **Solution:** Python script scans logs and extracts lines with “ERROR” or “WARN,” saving them into a separate file.
* **Value:** Speeds up incident analysis, helps teams quickly find issues.

---

### 🔹 Python Script – System Health Monitor

* **Problem:** Need quick visibility into system health.
* **Solution:** Script checks CPU, memory, and disk usage, then outputs a summary.
* **Value:** Helps in proactive monitoring and quick troubleshooting.

---

### 🔹 Grafana + Prometheus Dashboard

* **Problem:** No easy visualization of system metrics.
* **Solution:** Prometheus collects data; Grafana visualizes CPU, RAM, disk usage in a dashboard.
* **Value:** Provides live monitoring and alerting for better incident response.

---

### 🔹 Cloud Project – Simple Web App Deployment (AWS/Azure)

* **Problem:** Need to learn cloud deployment basics.
* **Solution:** Deployed a sample web app on AWS EC2 (or Azure VM), added CloudWatch/Azure Monitor alerts.
* **Value:** Hands-on cloud exposure, showing ability to deploy and monitor apps.

---

### 🔹 Kubernetes Deployment (Minikube)

* **Problem:** Applications need scalable deployments.
* **Solution:** Used Minikube to deploy a containerized app, scaled pods, and exposed service.
* **Value:** Practical understanding of Kubernetes basics (deployment, scaling, services).

---

### 🔹 CI/CD Pipeline (GitHub Actions / Jenkins)

* **Problem:** Manual deployments are error-prone and slow.
* **Solution:** Created a pipeline to build and deploy a sample app automatically.
* **Value:** Demonstrates knowledge of continuous integration and delivery for faster releases.
