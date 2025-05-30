# 🔐 Cybersecurity Home Lab Setup

This repository documents the setup of my personal cybersecurity home lab designed to practice real-world penetration testing techniques.

---

## 🧰 Tools & Platforms Used

- **Kali Linux** (Attacker OS)
- **DVWA** - Damn Vulnerable Web Application
- **OWASP Juice Shop** (via Docker)
- **Metasploitable2** (Vulnerable VM)
- **VirtualBox** (VM management)
- **Docker** (for containerized Juice Shop)

---

## 🛠️ System Requirements

- OS: Kali Linux (VM or host)
- Virtualization: VirtualBox/VMware
- RAM: Minimum 6–8 GB recommended
- Disk: 50+ GB free space

---

## ⚙️ Installation Steps

### 1. Install DVWA
```bash
sudo apt update
sudo apt install dvwa -y
