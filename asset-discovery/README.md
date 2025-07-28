# 🔍 Module 1: Network Asset Discovery & Inventory

## 🧩 Part of: [Universal IT Security Automation Toolkit](../)

## 📌 Purpose:
A Python-based script that discovers devices on a given subnet using Nmap, extracts their key details (IP, MAC, OS, open ports), stores them in a MySQL database, and exports the inventory to JSON and CSV formats.

## 🏥 Use Cases:
- MSPs discovering new client devices
- Healthcare IT departments tracking IoT medical devices
- Government offices auditing LAN environments
- Energy sector monitoring edge devices

## ⚙️ Features:
✅ Scans subnet via Nmap  
✅ Auto-saves device info into MySQL  
✅ Detects added, removed, or changed devices  
✅ Outputs CSV & JSON reports  
✅ Easily schedulable via cron/Task Scheduler

## 🧪 Technologies:
- Python 3
- Nmap (with `python-nmap` wrapper)
- MySQL
- Pandas

## 🛠️ Installation:

```bash
git clone https://github.com/Sachin1219/universal-it-security-toolkit.git
cd universal-it-security-toolkit/asset-discovery
pip install -r requirements.txt
