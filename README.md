# Two Endpoint Dockerized Flask App

## Project Description
This is a simple Flask application with two endpoints, containerized using Docker.

## Endpoints

### Home Endpoint
GET /

Response:
{
  "message": "Welcome to my Dockerized Flask App"
}

### Health Check Endpoint
GET /health

Response:
{
  "status": "healthy"
}

---

## Technologies Used
- Python
- Flask
- Docker
- GitHub

---

## How To Run Locally

### Install dependencies
pip install -r requirements.txt

### Run app
python app.py

---

## How To Run With Docker

### Build Image
docker build -t flask-app .

### Run Container
docker run -p 5000:5000 flask-app

---

## Test Endpoints

http://localhost:5000/

http://localhost:5000/health

---

## Screenshots Required
- Docker version
- Docker build successful
- Docker container running
- Endpoints working in browser/Postman
- GitHub repo uploaded

# Hello World App with Docker CI/CD

## Project Overview

This project demonstrates:

- Python Flask Hello World App
- Docker Containerization
- GitHub Actions CI/CD Pipeline
- Automatic Push to Docker Hub

---

## Run Locally

docker build -t hello-app .
docker run -p 5000:5000 hello-app

Visit:
http://localhost:5000

---

## CI/CD Process

Whenever code is pushed to main branch:

1. GitHub Actions triggers
2. Builds Docker image
3. Logs into Docker Hub
4. Pushes image automatically

---

## Docker Hub Repo

https://hub.docker.com/r/YOURUSERNAME/hello-app

---

## Screenshots Required

- Docker build successful
- App running in browser
- GitHub Actions success
- Docker Hub image uploaded