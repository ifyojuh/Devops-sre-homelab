# 🧪 DevOps / SRE Homelab

A personal multi-node homelab built to simulate real-world DevOps and Site Reliability Engineering (SRE) environments.  
This project demonstrates hands-on experience with Linux servers, containerization, monitoring, automation, and incident response.

---

## 🎯 Project Goals
- Build a production-like infrastructure using virtualization
- Practice Linux system administration
- Deploy and manage containerized applications
- Implement monitoring and observability
- Automate routine operational tasks
- Simulate failures and perform recovery (SRE mindset)

---

## 🏗️ Architecture Overview
```
Windows Host (VirtualBox)
│
├── infra-node (Ubuntu Server)
│ ├── Linux users & permissions
│ └── SSH & networking
│
├── docker-node (Ubuntu Server)
│ ├── Docker & Docker Compose
│ ├── Nginx
│ ├── Redis
│ ├── MySQL
│ └── Sample application
│
└── monitor-node (Ubuntu Server)
├── Prometheus
├── Grafana
└── Node Exporter
```

---

## 🧰 Tools & Technologies
- Linux (Ubuntu Server 22.04)
- VirtualBox
- Docker & Docker Compose
- Prometheus
- Grafana
- Bash scripting
- SSH
- Git & GitHub

---

## 🧪 Lab Breakdown

### Lab 1: Linux Fundamentals
- Installed and configured Ubuntu Server
- Managed users, permissions, and services
- Enabled SSH access

### Lab 2: Multi-VM Infrastructure
- Built a 3-node virtual homelab
- Configured hostnames and networking
- Implemented SSH key-based authentication

### Lab 3: Docker & Containers
- Installed Docker on a dedicated node
- Deployed containerized services
- Managed volumes, ports, and logs

### Lab 4: Monitoring & Observability
- Deployed Prometheus for metrics collection
- Visualized system metrics using Grafana dashboards
- Monitored CPU, memory, disk, and containers

### Lab 5: Automation
- Wrote Bash scripts for maintenance tasks
- Scheduled cron jobs
- Improved system reliability through automation

### Lab 6: Failure & Recovery
- Simulated service and container failures
- Analyzed logs and metrics
- Restored services and documented incident response

---

## 🧠 SRE Concepts Applied
- Infrastructure isolation
- Observability & monitoring
- Automation & toil reduction
- Incident response
- Reliability testing

---

## 📈 Outcome
This homelab provides hands-on experience comparable to entry-level DevOps and SRE roles, reinforcing both technical and operational best practices.

---

## 🔮 Future Improvements
- Kubernetes (Minikube / Kind)
- CI/CD with GitHub Actions
- Infrastructure as Code using Terraform

---

## 👤 Author
**Ify Ojuh**  
Site Reliability Engineer 

🔗 GitHub: https://github.com/ifyojuh  
🌐 Portfolio: https://ifyojuh.com
