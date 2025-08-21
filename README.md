# 🛡️ CrowdSec + Caddy Integration (Docker Compose)

This project demonstrates how to integrate **CrowdSec** with **Caddy** (as a reverse proxy) using **Docker Compose**.  
It enables **real-time detection, protection, and blocking** of malicious traffic on web applications.

---

## Features
- ⚡ Easy setup with **Docker Compose**
- 🔄 Seamless integration with **Caddy reverse proxy**
- 🛡️ CrowdSec detection + mitigation of malicious IPs
- 📊 Centralized logging & dashboards
- 👥 Leverages **community-driven threat intelligence**

---

## Requirements
- **Caddy** installed and running as your reverse proxy  
- **Docker + Docker Compose**  
- A domain pointing to your server  

---

## Usage
1. Clone this repo:
   ```bash
   git clone https://github.com/Rushil-Labs/Crowdsec.git
   cd Crowdsec
   docker compose up -d
   docker compose logs -f crowdsec


