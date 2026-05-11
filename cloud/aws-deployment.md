# ☁️ AWS EC2 Deployment Guide

This document explains deployment of the frontend Docker application on AWS EC2.

---

# 🚀 EC2 Setup

## Instance Type
- Ubuntu Server
- t2.micro

---

# 🔐 Security Group Rules

| Type | Port |
|------|------|
| SSH  | 22   |
| HTTP | 80   |

---

# 🐳 Install Docker

```bash
sudo apt update
sudo apt install docker.io -y
```

---

# 📥 Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/microservices-devops-platform.git
```

---

# 🚀 Build Docker Image

```bash
docker build -t frontend-app ./frontend
```

---

# ▶️ Run Container

```bash
docker run -d -p 80:80 frontend-app
```

---

# 🌐 Access Application

```text
http://YOUR_PUBLIC_IP
```

---

# 🎯 Deployment Goals

- Cloud-native deployment
- Dockerized infrastructure
- DevOps automation workflow
