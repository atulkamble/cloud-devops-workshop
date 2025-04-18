# cloud-devops-workshop
This repository contains slides, hands-on lab files, and sample code used in the "Cloud &amp; DevOps Essentials: A Hands-On Workshop for Beginners" conducted in a 2-hour seminar format. The goal is to help participants get started with AWS, Git, CI/CD, and basic DevOps workflows.

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
