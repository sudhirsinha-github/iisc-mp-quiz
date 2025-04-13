# 🚴‍♀️ Bike Share Count Prediction API

This project demonstrates an end-to-end MLOps workflow:
- Model training and inference
- FastAPI-based model serving
- Docker containerization and deployment
- CI/CD automation with GitHub Actions
- Hosting via self-hosted runner on EC2

---

## 🔗 Repository

[GitHub Repo](https://github.com/snehapriya-bs/MLOps-Longquiz)

---

## 🌍 Deployed App

- **Swagger UI**: [http://13.60.44.17:8001/docs](http://13.60.44.17:8001/docs)  
- **Health Check**: [http://13.60.44.17:8001/api/v1/health](http://13.60.44.17:8001/api/v1/health)

---

## ⚙️ Infrastructure

- **EC2 Instance**: Public IP with TCP port 8001 open
- **Docker**: Installed and enabled for containerization
- **Self-Hosted Runner**: Connected to GitHub for CI/CD automation

---

## 🔐 Secrets

- `DOCKER_TOKEN` added to GitHub Secrets for DockerHub authentication

---

## 🛠 GitHub Actions Workflow

Workflow automates:
- Model training
- API service build
- Docker image creation and push
- Deployment using Docker

[View Workflow File](https://github.com/snehapriya-bs/MLOps-Longquiz/blob/main/.github/workflows/main.yml)

---

## 📦 Output

- Docker image pushed to DockerHub
- Inference endpoint active on EC2

---

## 👤 Author

**Sneha Priya B S**  
MLOps Long Quiz Submission
