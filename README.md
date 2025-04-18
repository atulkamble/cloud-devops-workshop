# cloud-devops-workshop
This repository contains slides, hands-on lab files, and sample code used in the "Cloud &amp; DevOps Essentials: A Hands-On Workshop for Beginners" conducted in a 2-hour seminar format. The goal is to help participants get started with AWS, Git, CI/CD, and basic DevOps workflows.

Here’s a complete and professional **Syllabus for a 2-Hour Cloud Computing & DevOps Workshop** with hands-on activities, tailored for a **seminar hall session at QA** (college/institute), including slides and certificate setup.

---

## 📘 **Workshop Title**  
**"Cloud & DevOps Essentials: A Hands-On Workshop for Beginners"**

---

## 🕒 **Duration**  
**2 Hours** (Seminar Mode – Live Demo + Participant Interaction)

---

## 🎯 **Workshop Objectives**

By the end of the session, participants will:
- Grasp the fundamentals of Cloud Computing and DevOps
- Learn about tools like AWS, Git, Jenkins, and CI/CD pipelines
- Perform basic hands-on using GitHub + AWS + CodePipeline
- Understand real-world use cases and career paths

---

## 🧩 **Workshop Schedule & Syllabus**

| Time Slot | Topic | Format |
|-----------|--------|--------|
| 0:00 – 0:20 | **Cloud Computing & DevOps Introduction** <br>☁️ What is Cloud Computing?<br>🔧 What is DevOps?<br>🔄 Traditional vs DevOps Lifecycle | Presentation |
| 0:20 – 0:35 | **AWS & DevOps Tools Overview** <br>✔️ AWS (EC2, S3, IAM basics)<br>✔️ Git & GitHub<br>✔️ CI/CD with Jenkins & AWS CodePipeline | Presentation |
| 0:35 – 0:45 | **Use Cases & Real-world Applications** <br>🚀 Web App Deployment Example<br>💡 DevOps in Industry<br>👨‍💻 Cloud Projects Examples | Live Demo |
| 0:45 – 1:30 | **Hands-On Lab Activity** <br>🧪 **Task 1:** Clone from GitHub Repo<br>🧪 **Task 2:** Make a small change and push<br>🧪 **Task 3:** Trigger CI/CD Pipeline on AWS (CodePipeline)<br>🧪 **Task 4 (Optional):** Deploy basic app on EC2 | Guided Hands-On |
| 1:30 – 1:45 | **Career Roadmap & Certifications** <br>🎓 AWS DevOps Cert Path<br>💼 DevOps Job Roles<br>📈 Salary Trends & Job Sites | Presentation + Interaction |
| 1:45 – 2:00 | **Q&A + Feedback + Certificate Distribution** | Open Forum |

---

## 💻 **Tools/Requirements for Hands-on**
- AWS Free Tier Account
- GitHub Account
- Laptop with Internet
- Pre-installed Git, VS Code (optional)

---

## 📂 **Workshop Slides Download (PDF & PPT)**  
🎓 [**Download Slides PDF**](#)  
🎓 [**Download Slides PPT (PowerPoint)**](#)  
*(Let me know your branding/logo to personalize)*

---

## 📜 **Certificate of Completion (Sample Template)**

---

**Cloudnautic Technologies**  
🟦 *Certificate of Participation*

This is to certify that  
**_<<Participant Name>>_**  
has successfully completed the  
**"Cloud & DevOps Essentials: A Hands-On Workshop"**  
held on _<<Date>>_ at _<<Institute/QA>>_

Signature: _______________  
**Atul Kamble**, Cloud Solutions Architect  
🌐 www.cloudnautic.com

---

## 📥 What’s Next?
Would you like me to:
1. Generate the **PowerPoint Slides** now?
2. Create the **Completion Certificate** in Canva or PDF format?
3. Add **Post-Workshop Quiz**, **Feedback Form**, or **WhatsApp Group Link**?

Just say “Yes” to any/all and I’ll start right away 🚀

Here's a complete structure for your GitHub project repository for the **"Cloud & DevOps Essentials Workshop"**, including:

- ✅ Description  
- ✅ License (MIT)  
- ✅ `README.md`  
- ✅ Suggested Repo Name  
- ✅ Demo Codes (EC2 setup, GitHub push, AWS CodePipeline)  

---

## 📁 Suggested Repo Name
```
cloud-devops-workshop-qa
```

---

## 📄 Description
> This repository contains slides, hands-on lab files, and sample code used in the "Cloud & DevOps Essentials: A Hands-On Workshop for Beginners" conducted in a 2-hour seminar format. The goal is to help participants get started with AWS, Git, CI/CD, and basic DevOps workflows.

---

## ⚖️ License (MIT License)

```txt
MIT License

Copyright (c) 2025 Cloudnautic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...

[...license content continues, I can attach full if needed...]
```

---

## 📘 `README.md`

```markdown
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
  ```

### 2️⃣ Push Code to GitHub

- Clone repo:
  ```bash
  git clone https://github.com/YOUR_USERNAME/cloud-devops-workshop-qa.git
  cd cloud-devops-workshop-qa
  ```

- Edit `index.html` and push:
  ```bash
  git add .
  git commit -m "Updated web page"
  git push origin main
  ```

### 3️⃣ Deploy via AWS CodePipeline

- Configure Source: GitHub
- Build: AWS CodeBuild (or skip)
- Deploy: EC2 or S3 Static Site

---

## 📷 Slides & Certificate

- Slides: [Download PDF](#)
- Certificate: [Canva/Printable Version](#)

---

## 🧑‍💼 Trainer

**Atul Kamble**  
Founder & CEO, Cloudnautic  
🔗 [LinkedIn](https://linkedin.com/in/atuljkamble) | 🌐 [Cloudnautic](https://cloudnautic.com)

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) file for details.
```

---

## 🧪 Demo Code Samples

**HTML Page for EC2:**
```html
<!-- index.html -->
<!DOCTYPE html>
<html>
  <head>
    <title>Cloud Workshop</title>
  </head>
  <body>
    <h1>Hello from Cloud & DevOps Workshop @ QA!</h1>
  </body>
</html>
```

**Sample BuildSpec for AWS CodeBuild (Optional):**
```yaml
# buildspec.yml
version: 0.2
phases:
  install:
    commands:
      - echo Installing...
  build:
    commands:
      - echo Building the app...
artifacts:
  files:
    - '**/*'
```

---

## ✅ Next Steps
Would you like me to:
1. Package this as a downloadable **GitHub-ready zip**?
2. Upload to your GitHub repo or create a public one for you?
3. Add a Canva or PDF version of the certificate with your branding?

Let me know what you’d like me to generate next!
