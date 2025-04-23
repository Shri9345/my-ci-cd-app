# CI/CD Pipeline with GitHub Actions & Docker

## 🚀 Objective
Set up a CI/CD pipeline that:
- Builds a Docker image
- Runs automated tests
- Pushes the image to Docker Hub
- Deploys the image on an AWS EC2 Ubuntu 22.04 instance

## 🛠️ Tools Used
- GitHub Actions
- Docker
- Docker Hub
- AWS EC2 (Ubuntu 22.04)
- Python + Flask


## 🔁 CI/CD Workflow
- GitHub Action triggers on push to `main`
- Installs dependencies and runs tests
- Builds and pushes Docker image to Docker Hub

## 🧪 How to Run Locally
```bash
docker build -t my-app .
docker run -p 5000:5000 my-app

