# 🚴‍♀️ Bike Share Count Prediction API

This project demonstrates an end-to-end MLOps workflow:
- Model training and inference
- FastAPI-based model serving
- Docker containerization and deployment
- CI/CD automation with GitHub Actions
- Hosting via self-hosted runner on EC2

---

## 🔗 Repository

GitHub Repo
---
https://github.com/sudhirsinha-github/iisc-mp-quiz/


## 🌍 Deployed App

- **Swagger UI**: http://13.60.44.17:8001/docs  
- **Health Check**: http://13.60.44.17:8001/api/v1/health

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

View Workflow File

---

## 📦 Output

- Docker image pushed to DockerHub
- Inference endpoint active on EC2

---

## 📊 Project Submission Details

### **Project Overview:**
The Bike Share Count Prediction API aims to predict the number of bike shares in a given area using machine learning models. This project showcases the integration of MLOps practices to ensure efficient model deployment and maintenance.

### **Objectives:**
- Develop a predictive model for bike share counts.
- Implement a scalable API for model inference.
- Automate the deployment process using CI/CD pipelines.
- Ensure robust monitoring and maintenance of the deployed model.

### **Methodology:**
1. **Data Collection and Preprocessing:**
   - Gather historical bike share data.
   - Clean and preprocess the data for model training.

2. **Model Development:**
   - Train machine learning models using the preprocessed data.
   - Evaluate model performance and select the best model.

3. **API Development:**
   - Create a FastAPI-based service for model inference.
   - Implement endpoints for predictions and health checks.

4. **Containerization and Deployment:**
   - Containerize the API using Docker.
   - Deploy the containerized application on an EC2 instance.

5. **CI/CD Automation:**
   - Set up GitHub Actions for automated testing, building, and deployment.
   - Use a self-hosted runner on EC2 for continuous integration and deployment.

### **Results:**
- Successfully deployed the prediction API.
- Achieved accurate predictions for bike share counts.
- Automated the deployment process, ensuring seamless updates and maintenance.

### **Future Work:**
- Enhance the model with additional features and data sources.
- Implement advanced monitoring and alerting mechanisms.
- Explore scalability options for handling increased traffic.
