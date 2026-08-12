# Dockerized Django Application – AWS EC2

A Django web application containerized and deployed on AWS EC2 using Docker Compose, Nginx and MySQL.

## Technologies Used

- Django
- Python
- Docker
- Docker Compose
- Nginx
- MySQL
- AWS EC2
- Linux
- Git & GitHub

## Deployment Architecture

User
↓
Nginx
↓
Django Application
↓
MySQL

## Docker Containers

The application uses separate containers for:

- Django application
- Nginx
- MySQL

## Deployment

The application was deployed on an AWS EC2 instance using Docker Compose.

Nginx was configured as a reverse proxy to forward incoming HTTP requests to the Django application.

## Application Screenshots

### My Notes Application

![My Notes Application](adding%20notes.jpeg)

### Final Application

![Final Application](final%20notes.jpeg)

## Project Highlights

- Containerized Django application using Docker
- Configured Docker Compose for multi-container deployment
- Configured Nginx as a reverse proxy
- Connected Django application with MySQL
- Deployed application on AWS EC2
- Configured Linux server environment
- Verified application using browser and curl

