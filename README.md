

# HNG13 DevOps Stage 0

**Name:** Gaul Penelope Princess Anuoluwa
**Slack Username:** PenelopeG

---

## 📘 Project Description

This project is part of the **HNG13 DevOps Stage 0** task.
It involves deploying an **NGINX web server** and serving a **custom HTML webpage** accessible from the internet.

For this setup, I deployed the project **locally** on my **Windows machine** using **WSL (Windows Subsystem for Linux)** with **Ubuntu**, **NGINX**, and **ngrok** for port forwarding to make the local server publicly accessible.

The webpage displays a personalized welcome message along with deployment details, fulfilling the task requirements.

---

## 🌐 Server Details

**Server IP:** 172.30.233.92
**Server Type:** Local deployment via WSL and ngrok
**Operating System:** Ubuntu (on WSL)
**Public URL:** [https://translational-polyploidic-destiny.ngrok-free.dev/](https://translational-polyploidic-destiny.ngrok-free.dev/)
**Deployed On:** 18th October 2025

**Webpage Message:**

> Welcome to DevOps Stage 0 — Gaul Penelope Princess Anuoluwa / PenelopeG
> Successfully deployed on Ubuntu
>
> Deployed: 18th October 2025

---

## 🧰 Technologies Used

* 🐧 **Ubuntu (via WSL)** — Linux environment on Windows
* 🌐 **NGINX** — web server
* 💻 **HTML** — custom webpage
* 🔗 **ngrok** — port forwarding / tunneling
* 🧭 **GitHub** — version control and documentation

---

## 🚀 Steps Performed

1. Installed **WSL** and set up **Ubuntu** on Windows.
2. Installed **NGINX** using:

   ```bash
   sudo apt install nginx
   ```
3. Verified NGINX was running locally on port **80**.
4. Replaced the default `index.html` file with a custom version containing:

   * Full name and Slack username
   * Platform (**Ubuntu on WSL**)
   * Deployment date (**18th October 2025**)
5. Verified the page locally via `http://localhost`.
6. Installed **ngrok** and started a tunnel to expose port 80:

   ```bash
   ngrok http 80
   ```
7. Copied the generated **ngrok public URL** and confirmed global accessibility.

---

## ✅ Verification

The webpage is live and publicly accessible at the link below:
🔗 [https://translational-polyploidic-destiny.ngrok-free.dev/](https://translational-polyploidic-destiny.ngrok-free.dev/)

---

**End of README**

---
