# 🚀 HNG13 DevOps Stage 0 Project  

[![NGINX](https://img.shields.io/badge/Web%20Server-NGINX-green?style=flat-square&logo=nginx)](https://nginx.org/)  
[![Pop!_OS](https://img.shields.io/badge/OS-Pop!__OS-blue?style=flat-square&logo=system76)](https://pop.system76.com/)   

---

## 👤 Author  
**Name:** Ojomu Gbolahan Fadilulahi  
**Slack Username:** @Ordixian  

---

## 📖 Project Description  
This is my **Stage 0 DevOps Project** for the **HNG13 Internship**.  
It deploys an **NGINX web server** that serves a **custom HTML page** over HTTP.  
The project was executed on **Pop!_OS** and deployed to an **AWS EC2 instance (IP: 13.60.88.36)**, making it publicly accessible from the internet.

---

## 🌐 Deployment Details  
**Server URL:** [http://13.60.88.36](http://13.60.88.36)  
**Deployed On:** 18th October 2025  
**Platform:** AWS EC2  
**Web Server:** NGINX  

---

## ⚙️ Implementation Steps  
1. Provisioned a **VPS** using **AWS EC2 (Ubuntu 22.04)**.  
2. Transferred the custom HTML file via SSH to `/var/www/html/index.html`.  
3. Installed and configured **NGINX** to serve the page.  
4. Opened **port 80 (HTTP)** for inbound traffic via the AWS Security Group.  
5. Restarted NGINX and verified accessibility from external browsers.  

---

## 🧰 Tech Stack  
| Category | Tool |
|-----------|------|
| **Operating System** | Pop!_OS (Linux-based) |
| **Web Server** | NGINX |
| **Frontend** | HTML & CSS |
| **Deployment Platform** | AWS EC2 |

---

## ✅ Verification  
Live Project: 👉 [http://13.60.88.36](http://13.60.88.36)  

Successfully deployed using **AWS EC2 + NGINX** 🟢  

---

⭐ **HNG13 DevOps Track — Stage 0 Submission**  
Built with 💻 Linux, ☕ focus, and a dash of 🔥 persistence.
