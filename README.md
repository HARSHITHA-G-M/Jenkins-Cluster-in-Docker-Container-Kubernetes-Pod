Jenkins Cluster in Docker & Kubernetes
🚀 A complete Jenkins Master-Agent setup manually built from scratch using custom Docker images and deployed as scalable agents in Kubernetes.

📌 Project Overview
This project demonstrates:
✅ Custom Jenkins Master running in a Docker container (no prebuilt images)
✅ Jenkins Agents running as Kubernetes Pods
✅ Master-Agent communication for CI/CD pipelines
✅ Local development using Minikube on Ubuntu (WSL Compatible)

🛠️ Tech Stack
Jenkins (Custom-built)
Docker
Kubernetes (Minikube)
Ubuntu 20.04 (WSL Compatible)

📂 Project Structure
jenkins_cluster_project/
├── Dockerfile.master          # Custom Jenkins Master image
├── Dockerfile.agent           # Custom Jenkins Agent image
├── jenkins-master-compose.yml # Docker Compose file to run Jenkins Master
└── agent-deployment.yaml      # Kubernetes deployment for Jenkins Agents

