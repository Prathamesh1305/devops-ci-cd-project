# 🚀 CI/CD Pipeline for Containerized Web Application using Jenkins, Docker & AWS EC2

## 📌 Project Overview

This project demonstrates the implementation of a **complete DevOps CI/CD pipeline** to automate the build, containerization, and deployment of a web application using **GitHub, Jenkins, Docker, and AWS EC2**.

The goal of this project is to showcase **real-world DevOps practices** including continuous integration, continuous deployment, infrastructure automation, and container-based application delivery.

---

## 🎯 Project Objectives

* Automate application build and deployment using Jenkins.
* Containerize the web application using Docker.
* Push Docker images to Docker Hub.
* Deploy containerized application on AWS EC2.
* Implement a fully automated CI/CD workflow triggered by GitHub commits.

---

## 🛠️ Tech Stack & Tools

* **Version Control:** Git, GitHub
* **CI/CD Tool:** Jenkins
* **Containerization:** Docker, Docker Hub
* **Cloud Platform:** AWS EC2 (Amazon Linux)
* **Web Server:** Nginx
* **OS & Scripting:** Linux, Shell Script

---

## 🏗️ Project Architecture

```
Developer → GitHub → Jenkins → Docker Build → Docker Hub → AWS EC2 → Live Deployment
```

### Flow Explanation:

1. Developer pushes code to GitHub repository.
2. Jenkins automatically triggers the CI/CD pipeline.
3. Jenkins builds Docker image from Dockerfile.
4. Docker image is pushed to Docker Hub.
5. AWS EC2 pulls the latest image and deploys the container.

---

## 📂 Project Folder Structure

```
devops-ci-cd-project
│
├── app/
│   └── index.html
│
├── Dockerfile
├── Jenkinsfile
├── deploy.sh
└── README.md
```

---

## ⚙️ CI/CD Pipeline Workflow

1. Code commit pushed to GitHub
2. Jenkins webhook triggers pipeline
3. Jenkins clones repository
4. Docker image build
5. Image pushed to Docker Hub
6. Deployment on AWS EC2 using Docker container

---

## 🚀 Key Learnings

* CI/CD pipeline creation using Jenkins
* Docker image creation and container deployment
* Cloud-based deployment using AWS EC2
* Automation of build and deployment process
* Real-world DevOps workflow implementation

---

## 📈 Future Enhancements

* Kubernetes deployment using EKS
* Infrastructure automation using Terraform
* Monitoring with Prometheus & Grafana
* Blue-Green deployment strategy

---

## 👨‍💻 Author

**Prathamesh Santosh Mahajan**
B.Tech Computer Engineer |

📧 Email: [prathameshmahajan0802@gmail.com]
🔗 GitHub: [https://github.com/Prathamesh1305]

---

⭐ If you like this project, don't forget to **star the repository**!
