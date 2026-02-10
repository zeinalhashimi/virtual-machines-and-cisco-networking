Project Overview
This project is part of the IT Platforms final project.
The goal of Task 5 is to demonstrate how a simple web application can be built using Python Flask and deployed inside a Docker container, following modern DevOps practices.
The application runs in a containerized environment and displays a basic web page when accessed through a browser.
Technologies Used
Python 3
Flask (Web framework)
Docker
HTML (Jinja2 templates)
Project Structure
IT_Platforms_Project/
│
├── app.py
├── Dockerfile
├── requirements.txt
├── templates/
│   └── index.html
└── README.md
Application Description
The Flask application listens on port 8080
When the application runs, it displays a simple web page
The application is containerized using Docker so it can run consistently on any system
How to Run the Project
1. Build the Docker image
docker build -t flask-app .
2. Run the Docker container
docker run -p 8080:8080 flask-app
3. Access the application
Open a browser and go to:
http://localhost:8080
Twelve-Factor App Principles
This project follows basic Twelve-Factor App principles:
The application is packaged as a Docker container
Dependencies are explicitly declared
Configuration can be managed using environment variables
The app runs as a stateless service
