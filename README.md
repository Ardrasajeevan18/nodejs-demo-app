# CI/CD Pipeline for Node.js App

## Description
This project automates the deployment of a Node.js application using GitHub Actions and Docker. The pipeline builds, tests, and deploys the app to Docker Hub on every code push.

## How It Works
1. Push code to GitHub
2. GitHub Actions:
   - Installs dependencies
   - Runs tests
   - Builds Docker image
   - Pushes to Docker Hub

## Setup
1. Add these secrets in GitHub:
   - `DOCKER_HUB_USERNAME`
   - `DOCKER_HUB_TOKEN`
2. Push to `main` branch to trigger

## Files
- `.github/workflows/main.yml` - Pipeline definition
- `Dockerfile` - Container configuration

## Result
✅ Automated deployments  
✅ Containerized application  
✅ Secure credential handling

---

🛠 **Tools**: GitHub Actions, Docker, Node.js  
