# Dockerized Node.js Application

## Overview
A simple Node.js web application containerized using Docker.

## Technologies
- Node.js
- Docker
- GitHub
- Linux

## Project Structure

myapp/
├── Dockerfile
├── app.js
|── package.json


## Architecture Diagram

![Architecture](Node.js%20App.png)

## Build Docker Image
```bash
docker build -t myapp .
```

## Run Docker Container
```bash
docker run -d -p 3000:3000 myapp
```

## Access Application
```text
http://localhost:3000
```

## Learning Outcomes
- Built a Node.js application
- Created a Docker image
- Ran containers using Docker
- Exposed application ports
- Managed application deployment using containers
