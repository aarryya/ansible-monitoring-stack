# 🚀 Ansible Monitoring Stack (Prometheus + Grafana + Alertmanager)

## 📌 Project Overview

This project automates the setup of a complete monitoring stack using Ansible on AWS EC2.

## 🛠️ Technologies Used

* AWS EC2
* Ansible
* Prometheus
* Grafana
* Alertmanager

## ⚙️ What This Project Does

* Automates installation of Prometheus server
* Installs and configures Grafana
* Sets up Alertmanager
* Uses Ansible playbooks for automation

## 📂 Project Structure

```
.
├── inventory
├── grafana-installation.yml
├── prometheus-server-installation.yml
├── alertmanager-installation.yml
├── node-exporter-installation.yml
```

## 🚀 How to Run

1. Update inventory file:

```
[prometheus-server]
<your-ec2-ip>
```

2. Run playbooks:

```
ansible-playbook -i inventory grafana-installation.yml
ansible-playbook -i inventory prometheus-server-installation.yml
ansible-playbook -i inventory alertmanager-installation.yml
```

## 🌐 Access Services

* Grafana → http://<IP>:3000
* Prometheus → http://<IP>:9090
* Alertmanager → http://<IP>:9093

## 📸 Screenshots

(Add your screenshots here)

## 📚 Learning Outcome

* Infrastructure automation using Ansible
* Monitoring stack deployment
* AWS EC2 configuration

---

⭐ If you like this project, give it a star!
