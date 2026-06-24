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

docker build -t myapp .

## Run Container

docker run -d -p 3000:3000 myapp

## Access Application

http://localhost:3000
