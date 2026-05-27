# DevOps Practice Labs

This repository contains hands-on DevOps practice labs, commands, exercises, and real-world implementation tasks completed during my DevOps learning journey.

The main objective of this repository is to build practical DevOps skills by performing real-time labs and understanding industry-standard tools and workflows.

---

# Project Objective

This repository is designed to provide practical experience with DevOps tools, Linux administration, cloud concepts, CI/CD pipelines, containerization, automation, and infrastructure management.

The project focuses on:
- Hands-on DevOps learning
- Real-world lab practice
- Command-line expertise
- CI/CD implementation
- Containerization
- Automation
- Infrastructure management
- Troubleshooting skills

---

# Technologies & Tools Covered

- Linux
- Git & GitHub
- Docker
- GitHub Actions
- Jenkins
- Kubernetes
- Terraform
- Ansible
- AWS
- Shell Scripting
- CI/CD Pipelines
- Networking Basics

---

# Topics Covered

## 1. Linux Administration

Linux basic to advanced commands and server management.

### Commands Practiced
```bash
pwd
ls -la
cd
mkdir
rm -rf
chmod
chown
grep
find
top
ps -ef
df -h
free -m
netstat -tulnp
systemctl status
```

### Skills Learned
- File management
- User management
- Process management
- Disk monitoring
- Log monitoring
- Service management
- Linux troubleshooting

---

# 2. Git & GitHub

Version control and repository management using Git and GitHub.

### Commands Practiced
```bash
git init
git clone
git add .
git commit -m "message"
git push
git pull
git branch
git checkout
git merge
```

### Skills Learned
- Version control
- Branching strategy
- Repository management
- Collaboration workflow
- GitHub integration

---

# 3. Docker

Containerization and Docker fundamentals.

### Commands Practiced
```bash
docker pull nginx
docker images
docker ps
docker run -d -p 80:80 nginx
docker stop container_id
docker rm container_id
docker build -t myapp .
```

### Skills Learned
- Docker images
- Docker containers
- Dockerfile creation
- Port mapping
- Container lifecycle management

---

# 4. CI/CD Pipelines

Basic Continuous Integration and Continuous Deployment workflows.

### Topics Practiced
- GitHub Actions
- Jenkins basics
- Automated pipelines
- Build automation
- Deployment automation

### Sample Workflow
```yaml
name: CI Pipeline

on:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout Code
        uses: actions/checkout@v3

      - name: Run Build
        run: echo "Pipeline Running Successfully"
```

---

# 5. Kubernetes Basics

Container orchestration concepts and commands.

### Commands Practiced
```bash
kubectl get pods
kubectl get nodes
kubectl apply -f deployment.yml
kubectl describe pod pod-name
kubectl logs pod-name
```

### Skills Learned
- Pods
- Deployments
- Services
- YAML manifests
- Cluster basics

---

# 6. Terraform

Infrastructure as Code (IaC) fundamentals.

### Commands Practiced
```bash
terraform init
terraform plan
terraform apply
terraform destroy
```

### Skills Learned
- Infrastructure provisioning
- Automation
- Cloud resource management
- Terraform workflow

---

# 7. Ansible

Configuration management and automation.

### Commands Practiced
```bash
ansible all -m ping
ansible-playbook playbook.yml
```

### Skills Learned
- Automation
- Configuration management
- Playbooks
- Inventory management

---

# 8. AWS Basics

Cloud computing and AWS services.

### Services Practiced
- EC2
- S3
- IAM
- VPC
- Security Groups

### Skills Learned
- Cloud basics
- Virtual machines
- Cloud networking
- Access management

---

# Repository Structure

```bash
devops-practice-labs/
│
├── linux/
├── git-github/
├── docker/
├── kubernetes/
├── terraform/
├── ansible/
├── aws/
├── cicd/
├── scripts/
└── README.md
```

---

# Real-Time DevOps Scenarios Practiced

- Website down troubleshooting
- CPU utilization issue
- Disk space issue
- SSH connection troubleshooting
- Jenkins pipeline debugging
- Docker container management
- Service monitoring
- Log analysis
- Port accessibility troubleshooting

---

# Learning Outcomes

After completing these labs, I learned:
- Linux administration
- Version control workflow
- Containerization concepts
- CI/CD pipeline basics
- Infrastructure automation
- Cloud fundamentals
- Troubleshooting techniques
- DevOps workflow understanding

---

# Real-World Use Cases

These DevOps practices are commonly used in:
- Software deployment
- Cloud infrastructure
- Automation pipelines
- Monitoring systems
- Container orchestration
- Enterprise DevOps environments

---

# Future Improvements

Future enhancements planned:
- Advanced Kubernetes
- Helm charts
- ArgoCD
- Monitoring with Prometheus & Grafana
- Advanced AWS deployment
- Multi-stage CI/CD pipelines
- Production-grade infrastructure setup

---

# Author

## Mustafa Balasinorwala

DevOps Enthusiast

GitHub:
https://github.com/MustafaBalasinorwala91

---

# Conclusion

This repository represents my hands-on DevOps practice and continuous learning journey through practical labs and real-world implementation exercises.

The labs helped me understand modern DevOps workflows, automation practices, cloud concepts, and deployment strategies used in real industry environments.
