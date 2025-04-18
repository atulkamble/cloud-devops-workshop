# cloud-devops-workshop
This repository contains slides, hands-on lab files, and sample code used in the "Cloud &amp; DevOps Essentials: A Hands-On Workshop for Beginners" conducted in a 2-hour seminar format. The goal is to help participants get started with AWS, Git, CI/CD, and basic DevOps workflows.

# Cloud & DevOps Essentials Workshop (QA Edition)

🚀 A 2-hour practical introduction to Cloud & DevOps using AWS, Git, and CodePipeline.

## 📚 Workshop Contents

- Cloud Basics (IaaS, PaaS, SaaS)
- DevOps Lifecycle and Tools
- Hands-on with AWS EC2, Git, and CodePipeline
- Sample App Deployment Workflow

---

## 💡 Hands-On Lab

### 1️⃣ Setup EC2 via AWS Console

- Launch Amazon Linux 2 t2.micro
- Enable HTTP traffic
- Install Apache:
  ```bash
  sudo yum install httpd -y
  sudo systemctl start httpd
  echo "<h1>Hello from Cloud Workshop</h1>" | sudo tee /var/www/html/index.html

