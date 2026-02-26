#  Automated CI/CD Pipeline for a Python Web App

Welcome to my first end-to-end **DevOps CI/CD Project**! This repository demonstrates how to automate the deployment of a containerized application using modern cloud and DevOps tools.

###  **Tech Stack Used**
* **Cloud Provider:** AWS EC2 (Ubuntu Linux)
* **Version Control:** Git & GitHub
* **Containerization:** Docker
* **Configuration Management:** Ansible
* **CI/CD Automation:** Jenkins
* **Application:** Python (Flask)

### **Project Architecture & Workflow**
1. **Code Commit:** Developer pushes Python code (`app.py`) and `Dockerfile` to this GitHub repository.
2. **Continuous Integration:** **Jenkins** detects the code change and pulls the latest updates to the AWS server.
3. **Configuration & Build:** Jenkins triggers an **Ansible Playbook** (`deploy.yml`).
4. **Containerization:** Ansible automatically builds a fresh **Docker Image** from the new code and removes the old container.
5. **Continuous Deployment:** Ansible deploys the new **Docker Container**, making the live web app available on Port 5000.

### **Author**
**Arbaj** Actively building advanced DevOps skills and transitioning from theoretical knowledge to hands-on cloud automation.
