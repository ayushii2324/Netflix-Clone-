# Netflix-Clone-
🚀 Deploying a Netflix Clone on AWS with Jenkins CI/CD & DevSecOps
A complete DevSecOps CI/CD Pipeline Project where a Netflix Clone application is containerized, scanned for vulnerabilities, and deployed to the cloud using modern DevOps tools like Jenkins, Docker, Kubernetes, SonarQube, Trivy, and AWS.

📌 Project Overview
This project demonstrates how to implement a complete DevSecOps pipeline for a Netflix Clone application.

The pipeline includes:
Source Code Management with GitHub
Continuous Integration using Jenkins
Code Quality Analysis with SonarQube
Security Scanning using Trivy
Docker Image Build & Push
Kubernetes Deployment
Monitoring with Prometheus & Grafana
Cloud Deployment on AWS

🛠️ Tech Stack
| Category         | Tools Used           |
| ---------------- | -------------------- |
| CI/CD            | Jenkins              |
| Containerization | Docker               |
| Orchestration    | Kubernetes           |
| Security         | Trivy                |
| Code Quality     | SonarQube            |
| SCM              | Git & GitHub         |
| Cloud            | AWS EC2              |
| Monitoring       | Prometheus & Grafana |
| Web Server       | Nginx                |
| Application      | Netflix Clone        |

🏗️ DevSecOps Architecture
Developer → GitHub → Jenkins Pipeline
                      ↓
              SonarQube Scan
                      ↓
                Trivy Scan
                      ↓
             Docker Build & Push
                      ↓
             Kubernetes Deployment
                      ↓
                AWS Cloud Server
                      ↓
            Monitoring & Alerting

⚙️ Features
✅ CI/CD Automation with Jenkins
✅ Dockerized Netflix Clone Application
✅ Kubernetes Deployment
✅ Security Scanning with Trivy
✅ SonarQube Code Quality Checks
✅ AWS Cloud Deployment
✅ Monitoring with Prometheus & Grafana
✅ Production-like DevSecOps Workflow

📂 Project Structure
Netflix-Clone-DevSecOps/
│
├── Jenkinsfile
├── Dockerfile
├── deployment.yaml
├── service.yaml
├── prometheus.yml
├── grafana/
├── src/
├── public/
└── README.md

🔄 CI/CD Pipeline Stages
1️⃣ Clone Repository
Jenkins pulls the source code from GitHub.

2️⃣ SonarQube Analysis
Static code analysis and quality checks.

3️⃣ Trivy Security Scan
Scans Docker images and filesystem vulnerabilities.

4️⃣ Docker Build
Builds Docker image for the Netflix Clone app.

5️⃣ Push to DockerHub
Pushes the image to DockerHub Registry.

6️⃣ Kubernetes Deployment
Deploys the application into Kubernetes cluster.

7️⃣ Monitoring Setup
Prometheus and Grafana monitor application metrics.

☁️ AWS Deployment Steps
Launch EC2 Instance
Ubuntu 22.04
t2.large recommended
Install Required Tools
sudo apt update
sudo apt install docker.io -y
sudo apt install git -y

Install:

Jenkins
Docker
Kubernetes
Trivy
SonarQube

🐳 Docker Build Command
docker build -t netflix-clone .
docker run -d -p 3000:3000 netflix-clone

☸️ Kubernetes Deployment
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

📊 Monitoring Dashboard
Prometheus
Collects application metrics.
Grafana
Visualizes monitoring dashboards.

🔐 Security Implementation
Trivy vulnerability scanning
Secure Jenkins credentials
Docker image scanning
Kubernetes best practices

🚀 Future Enhancements
ArgoCD GitOps Deployment
Helm Charts
Terraform Infrastructure Automation
AWS EKS Deployment
Slack Notifications

👨‍💻 Author
Ayushii
DevOps & Cloud Enthusiast

GitHub: https://github.com/ayushii2324/Netflix-Clone-/edit/main/README.md
