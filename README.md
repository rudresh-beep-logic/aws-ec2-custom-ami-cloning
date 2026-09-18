# 📀 AWS EC2 Custom AMI Creation & Server Cloning Project

## 📌 Overview
This project demonstrates virtualization management in AWS by creating a **Golden AMI (Amazon Machine Image)** from a pre-configured Master Linux server and deploying cloned application instances instantly.

## 🔑 Core Concepts Covered
- **Virtualization:** Abstracting physical hardware into AWS EC2 virtual machines.
- **Tenancy:** Configuring shared vs. dedicated hardware tenancy for instances.
- **AMIs (Amazon Machine Images):** Capturing machine state, OS, and software dependencies into reusable templates.

---

## 🛠️ Implementation Steps
1. Launched a Master Ubuntu EC2 instance with pre-configured Nginx web services.
2. Created a custom **Golden AMI** (`Custom-Nginx-Gold-AMI`) from the running master instance.
3. Provisioned new EC2 instances directly using the custom AMI without running initialization scripts.
4. Verified configuration parity and immediate availability across cloned servers.

---

## 🎯 Key Learnings
- Accelerating application deployment using pre-baked Golden Images.
- Managing AMI lifecycle and backup strategy in cloud infrastructure.
