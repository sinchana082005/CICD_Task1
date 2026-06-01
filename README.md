# Node.js CI/CD Pipeline

![CI/CD](https://github.com/sinchana082005/CICD_Task1/actions/workflows/main.yml/badge.svg)

## Overview

This project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions, Jenkins, Docker, and Node.js.

## Technologies Used

* Node.js
* Express.js
* Docker
* GitHub Actions
* Jenkins
* Git
* GitHub

## CI/CD Workflow

1. Push code to GitHub
2. GitHub Actions triggers automatically
3. Jenkins fetches source code from GitHub
4. Dependencies are installed using npm
5. Docker image is built
6. Docker image is verified
7. Pipeline execution status is displayed in Jenkins

## Jenkins Pipeline Stages

* Install Dependencies
* Build Docker Image
* Verify Docker Image

## Run Locally

```bash
npm install
node app.js
```

## Run Using Docker

```bash
docker build -t cicd-task1 .
docker run -p 3000:3000 cicd-task1
```

## Repository Files

* app.js
* package.json
* package-lock.json
* Dockerfile
* Jenkinsfile
* README.md
* .github/workflows/main.yml

## Outcome

Successfully implemented a CI/CD pipeline using GitHub Actions, Jenkins, Docker, and Node.js.

## Author

Sinchana Naik
