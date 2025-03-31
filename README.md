# Dockerised Calculator Microservice

## Overview
This project Dockerises a simple calculator microservice built with **Node.js** and **Express.js**. It performs basic arithmetic operations through a web interface and includes logging and health checks.

## Features
- Dockerfile and Docker Compose setup
- Addition, Subtraction, Multiplication, Division
- Winston-based logging
- Health check with auto-restart
- Exposed on port 3000

## Getting Started

### 1. Clone the project
```bash
git clone https://github.com/MAYURA26-bot/sit737-2025-prac4.1P.git
```

### 2. Build Docker Image
```bash
docker build -t mayura1994/5.1p-calculator-web-app
```

### 3. Run the Container
```bash
docker run -p 3000:3000 mayura1994/5.1p-calculator-web-app
```
Access the app at: [http://localhost:3000](http://localhost:3000)

### 4. Run with Docker Compose
```bash
docker compose up
```

### 5. Check Container Logs
```bash
docker ps
# Get the container ID
```

## Docker Hub Link
Image hosted at:  
https://hub.docker.com/r/mayura1994/5.1p-calculator-web-app

## GitHub Repository
Code available at:  
https://github.com/MAYURA26-bot/sit737-2025-prac5.1P

## License
MIT License

