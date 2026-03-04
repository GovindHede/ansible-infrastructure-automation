# Infrastructure Automation using Ansible on AWS EC2

## 📌 Project Overview
This project demonstrates Infrastructure as Code (IaC) using Ansible to automate server configuration on AWS EC2 instances.

## 🚀 Features
- Automated Nginx installation
- Automated Docker installation
- Docker container deployment
- Role-based modular architecture
- Separate staging and production inventories
- Idempotent infrastructure configuration

## 🛠 Technologies Used
- Ansible
- AWS EC2
- Linux (Ubuntu)
- Docker
- Nginx
- Git

## 📂 Project Structure

ansible-infra-automation/
├── ansible.cfg
├── site.yml
├── inventory/
│   ├── staging
│   └── production
├── roles/
│   ├── nginx/
│   └── docker/

## ▶️ How to Run

1. Install Ansible
2. Configure inventory file
3. Run:

   ansible-playbook site.yml

## 🎯 Outcome
Reduced manual server configuration time and ensured consistent environment setup using Infrastructure as Code principles.

---

Author: Govind Hede
