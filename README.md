# IT Platforms Final Project  
**Group 10 – Winter 2025/2026**

## Project Overview

This project was developed as part of the **IT Platforms** course. The objective of the project is to demonstrate practical knowledge of modern IT platforms, including **virtual machines, networking concepts, containerization, and web application deployment**.

The project is divided into multiple tasks, each focusing on a different aspect of IT platforms. Together, these tasks show how infrastructure, networking, and application platforms interact in a real-world environment.

---

## Project Objectives

- Configure and manage **virtual machines**
- Apply fundamental **Cisco networking concepts**
- Understand platform-level services
- Deploy a web application using **Docker**
- Follow modern **platform best practices**
- Use **GitHub** for version control and collaboration

---

## Tasks Overview

### Task 1 – Virtual Machines
- Creation and configuration of virtual machines
- Understanding VM roles and system resources

### Task 2 – Networking
- Application of Cisco networking fundamentals
- IP addressing and network connectivity

### Task 3 – Platform Services
- Exploration of platform services
- Understanding service interaction within IT platforms

### Task 4 – System Integration
- Integration of virtual machines and networking
- Ensuring communication between system components

### Task 5 – Web Application Deployment (Flask & Docker)
- Development of a Python Flask web application
- Containerization using Docker
- Deployment of the application as a platform service

---

## Task 5 – Flask Application with Docker

### Description

Task 5 demonstrates the deployment of a simple web application using **Python Flask** inside a **Docker container**. The application runs as a platform service and displays a basic web page when accessed through a browser.

The task highlights the use of containerization to ensure consistency, portability, and ease of deployment.

---

### Technologies Used

- Python 3
- Flask
- Docker
- HTML (Jinja2 templates)
- Git and GitHub

---

## Project Structure

IT_Platforms_Project/
│
├── app.py
├── Dockerfile
├── requirements.txt
├── templates/
│ └── index.html
└── README.md

---

## How to Run Task 5

### 1. Build the Docker Image

```bash
docker build -t flask-app .
2. Run the Docker Container
docker run -p 8080:8080 flask-app
3. Access the Application
Open a browser and navigate to:
http://localhost:8080
