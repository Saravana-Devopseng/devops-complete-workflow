# 🚀 Complete DevOps Workflow Project

## 📋 Project Overview

A complete end-to-end DevOps workflow demonstrating containerization, version control, and cloud deployment.

**Live Website:** http://54.160.141.125:8080

## 🛠️ Technologies Used

- **Docker** - Containerization
- **Git & GitHub** - Version Control
- **AWS EC2** - Cloud Infrastructure
- **Nginx** - Web Server
- **Linux (Ubuntu)** - Operating System

## 📁 Project Structure
devops-complete-workflow/
├── index.html # Main website file
├── Dockerfile # Docker container instructions
└── README.md # Project documentation

## 🚀 Deployment Steps

### 1. Local Development
```bash
mkdir devops-complete-workflow
cd devops-complete-workflow
nano index.html
nano Dockerfile
```

### 2. Version Control with Git
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Saravana-Devopseng/devops-complete-workflow.git
git branch -M main
git push -u origin main
```

### 3. AWS EC2 Setup
- Launched Ubuntu EC2 instance (t2.micro)
- Configured Security Group (Port 22, 8080)
- SSH access with key pair

### 4. Docker Deployment on EC2
```bash
git clone https://github.com/Saravana-Devopseng/devops-complete-workflow.git
cd devops-complete-workflow
sudo apt update
sudo apt install docker.io -y
docker build -t my-nginx-app .
docker run -d -p 8080:80 --name my-app my-nginx-app
```

## 🌐 How It Works

1. **Code Development** - Created HTML website locally
2. **Containerization** - Packaged with Docker
3. **Version Control** - Saved on GitHub
4. **Cloud Deployment** - Deployed to AWS EC2
5. **Public Access** - Accessible worldwide

## 🎯 Key Learnings

- ✅ Git workflow (init, add, commit, push)
- ✅ Docker containerization (build, run)
- ✅ AWS EC2 instance management
- ✅ Linux command line operations
- ✅ Network security configuration
- ✅ CI/CD pipeline basics

## 👨‍💻 Author

**Saravana Kumar**  
Location: Kadirvedu, Tamil Nadu, India  
Date: May 3, 2026

## 📄 Documentation

Complete step-by-step guide with explanations available in repository.

---

⭐ **Star this repository if you found it helpful!**
