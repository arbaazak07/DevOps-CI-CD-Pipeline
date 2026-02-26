Automated CI/CD Pipeline for a Python Web App
This repository contains my first end-to-end DevOps project. It automates the deployment of a containerized Python application using a modern CI/CD workflow.

🛠️ Technologies Used
Infrastructure: AWS EC2 (Ubuntu Linux)

Version Control: Git & GitHub

Containerization: Docker

Configuration Management: Ansible

CI/CD Automation: Jenkins

Application: Python (Flask)

⚙️ How It Works
A simple Python Flask application is containerized using a Dockerfile.

An Ansible Playbook (deploy.yml) is written to automate the Docker build and run commands.

A Jenkins server is configured to pull the latest code from this repository.

Whenever new code is pushed, Jenkins automatically triggers the Ansible playbook, deploying the updated containerized app to the AWS server without manual intervention.
