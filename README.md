============================
Dockerized Python Application
============================

This repository contains a simple Python application containerized using Docker.

---

## Overview
- Python application: app.py
- Containerized with Dockerfile
- Dependencies listed in requirements.txt

---

## Advantages
- Easy to deploy anywhere with Docker
- Consistent environment for running the Python app
- Portable and scalable

---

## Files
- Dockerfile – Instructions to build the Docker image
- app.py – Python application
- requirements.txt – Python dependencies

---

## Usage

1. **Build the Docker image**
$ docker build -t python-app .

2. **Run the Docker container**
$ docker run -p 5000:5000 python-app

3. **Access the application**
- Open browser or use curl at http://localhost:5000

---

## References
- Docker: https://www.docker.com/
- Python: https://www.python.org/
