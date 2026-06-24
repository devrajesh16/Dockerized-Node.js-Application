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

```bash
docker build -t myapp .
```

```bash
docker run -d -p 3000:3000 myapp
```
```text
http://localhost:3000
```
