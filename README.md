# 🖥 Home Mini Company Infrastructure

### Not abandoned, but work is in progress.

## 📌 Project Overview

This project simulates a small company infrastructure with approximately 20 employees.

The goal is to demonstrate practical system administration skills by designing and configuring a secure Linux-based server environment, including user management, access control, firewall configuration, intrusion prevention, logging, and backup automation.

This is not just a basic Ubuntu installation — it represents a structured, policy-driven infrastructure setup.

---

## 🏢 Scenario

A small company with ~20 employees requires:

* Centralized Linux server
* Secure SSH access
* Role-based access control
* Network protection
* Log monitoring
* Automated backups

---

## 🛠 Implemented Features

### 1️⃣ Linux Server Setup

* Base system installation and hardening
* IP configuration
* Hostname and network configuration
* Configure several net interfaces(external/internal)

### 2️⃣ User & Group Management

* Creation of multiple users
* Department-based groups (e.g., IT, HR, Management)
* Proper file and directory permissions
* Principle of least privilege

### 3️⃣ Secure SSH Configuration

* Key-based authentication
* Disabled root login
* Changed default SSH port (optional)
* Restricted access via firewall rules

### 4️⃣ Firewall Configuration

* Implemented using:

  * `ufw` or `iptables`
* Only required ports opened
* Default deny policy

### 5️⃣ Fail2Ban Protection

* Brute-force attack mitigation
* SSH jail configuration
* Custom ban timing policies

### 6️⃣ Logging & Monitoring

* System log inspection
* Authentication log monitoring
* Custom log checks (optional)

### 7️⃣ Backup Automation

* Bash backup script
* Incremental backups
* Cron job scheduling
* Log file for backup status

---

## 📂 Repository Contents

* `/scripts`          → automation (backup, firewall setup, users)
* `/configs`         → netplan, sshd_config, ufw rules, etc
* `/architecture`     → network diagram, topology
* `/policies`        → security & access policies
* `/docs`             → implementation steps & explanations
* `README.md`         → overview проекта
---

## 🔐 Security Policy Highlights

* Role-based access control
* Restricted administrative privileges
* SSH hardening
* Firewall default deny strategy
* Automated intrusion response
* Regular backup schedule

---

## 🎯 What This Project Demonstrates

✔ Practical Linux system administration
✔ Security-first mindset
✔ Infrastructure planning
✔ Automation with Bash
✔ Understanding of real-world small business environments

## 📄 License

MIT License — feel free to use and contribute!
