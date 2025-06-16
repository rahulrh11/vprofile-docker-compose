# Vprofile Application on Containers using Docker Compose

This project demonstrates how to run the **Vprofile multi-tier web application** using **Docker Compose**. Instead of setting up each service on separate VMs, this containerized approach enables all components to run together efficiently within a single VM using Docker.

---

## 📦 Components Used

The Vprofile application includes the following services, each running as a container:
- **Nginx** – Web server & reverse proxy
- **Tomcat** – Hosts the Vprofile Java application
- **MySQL** – Backend database
- **RabbitMQ** – Message broker
- **Memcached** – Cache layer

---

## ✅ Prerequisites

- Vagrant & VirtualBox installed
- Git installed
- Minimum **2 GB free RAM**
- Internet connection to pull Docker images

---

## ⚙️ Setup Instructions

### 1. Download Vagrant Files
- Download the ZIP from the **course resources**.
- Extract it and choose the correct Vagrantfile:
  - `Windows`
  - `MacOS Intel`
  - `MacOS M1`

### 2. Create a Working Directory
```bash
mkdir F:/containerIntro
# Copy the correct Vagrantfile into this folder
