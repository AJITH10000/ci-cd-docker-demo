# CI/CD Pipeline with GitHub Actions & Docker

## Project Overview  
This project demonstrates a complete CI/CD pipeline setup that automates building, testing, and deploying a Dockerized application using GitHub Actions. The application is deployed locally using Minikube or a local VM, avoiding cloud dependencies.

## Objective  
- Automate the build and test process of a Docker image  
- Push the built image to Docker Hub  
- Deploy and run the image locally using Minikube or a local virtual machine  

## Tools Used  
- GitHub Actions for CI/CD workflow automation  
- Docker for containerizing the application  
- Docker Hub for hosting the Docker images  
- Minikube or local VM for local deployment and testing  
- docker-compose for managing local multi-container setups

## Setup and Usage

### Prerequisites  
- Docker installed locally  
- Minikube or a local VM setup (optional but recommended for deployment)  
- GitHub account with access to the repository  
- Docker Hub account for pushing and pulling images  

### How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/AJITH10000/ci-cd-docker-demo.git
   cd ci-cd-docker-demo

2. GitHub Actions automatically triggers on every push:
Runs automated tests
Builds Docker image
Pushes image to Docker Hub
3.Deploy locally:
Use Minikube or local VM to pull and run the Docker image from Docker Hub.
---

## GitHub Actions Workflow
The workflow is defined in .github/workflows/ci-cd.yml and includes:
1.Checkout code
2.Run tests
3.Build Docker image
4.Push image to Docker Hub

---
## Author
Ajith Kumar Reddy – https://github.com/AJITH10000
