# ✈️ Airline Reservation System - CI/CD Automation on AWS

![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-black)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange)

## 📖 Overview

This project demonstrates a complete DevOps workflow for deploying an Airline Reservation System using Git, GitHub, Jenkins, Docker, and AWS EC2.

The objective is to automate software delivery through Continuous Integration and Continuous Deployment (CI/CD), ensuring faster releases and reliable deployments.

---

## 🏗️ Architecture

```text
Developer
    │
    ▼
 GitHub Repository
    │
 GitHub Webhook
    ▼
 Jenkins Pipeline
    │
 ├── Build
 ├── Test
 ├── Docker Build
 └── Deploy
    ▼
 AWS EC2
    ▼
 Live Application
```

---

## 🚀 Application Homepage

![Homepage](screenshots/01_Homepage.png)

The homepage provides:

* Flight Search
* Ticket Booking
* User Authentication
* Booking Management
* Responsive Design

---

## 🔄 Git Workflow

### Repository

![Repository](screenshots/02_GitHub_Repository.png)

### Commit History

![Commit History](screenshots/03_Git_Commit_History.png)

### Pull Request Workflow

![Pull Request](screenshots/04_Pull_Request.png)

Workflow followed:

```bash
git checkout -b feature-booking
git add .
git commit -m "Add booking feature"
git push origin feature-booking
```

Feature Branch → Pull Request → Code Review → Merge

---

## ⚙️ Jenkins CI/CD Pipeline

### Jenkins Dashboard

![Jenkins Dashboard](screenshots/05_Jenkins_Dashboard.png)

### Successful Build

![Build Success](screenshots/06_Jenkins_Successful_Build.png)

Pipeline Stages:

* Checkout Source Code
* Build Application
* Execute Tests
* Build Docker Image
* Deploy Application

---

## 🧪 Automated Testing

![Test Report](screenshots/07_Test_Report.png)

Results:

| Metric       | Value |
| ------------ | ----- |
| Total Tests  | 87    |
| Passed       | 87    |
| Failed       | 0     |
| Success Rate | 100%  |

---

## 🐳 Docker Containerization

### Docker Images

![Docker Images](screenshots/08_Docker_Images.png)

### Running Containers

![Containers](screenshots/09_Running_Containers.png)

Docker ensures consistent deployment across environments.

---

## ☁️ AWS Deployment

![AWS EC2](screenshots/10_AWS_EC2.png)

Deployment Environment:

| Service           | Details    |
| ----------------- | ---------- |
| Cloud Provider    | AWS        |
| Region            | ap-south-1 |
| Service           | EC2        |
| Operating System  | Ubuntu     |
| Container Runtime | Docker     |

---

## 🌐 Live Application

![Live Application](screenshots/11_Live_Application.png)

Application successfully deployed and accessible through AWS EC2 Public IP.

---

## 🛠️ Tech Stack

### Frontend

* Angular
* HTML
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### DevOps

* Git
* GitHub
* Jenkins
* Docker
* AWS EC2

---

## 📂 Project Structure

```text
airline-reservation-system/

├── frontend/
├── backend/
├── docker/
├── jenkins/
├── screenshots/
├── README.md
└── .gitignore
```

---

## 📈 CI/CD Flow

```text
Code Commit
     ↓
GitHub Push
     ↓
Webhook Trigger
     ↓
Jenkins Build
     ↓
Automated Testing
     ↓
Docker Build
     ↓
AWS Deployment
     ↓
Application Live
```

---

## 👨‍💻 Author

**Onkar Kakde**

MCA Student | AWS & DevOps Enthusiast

GitHub: https://github.com/omkakde2003
