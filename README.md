
# DevOps Internship Task - Containerized App Deployment

## Project Overview
A simple static web application containerized using Docker
and served by Nginx on AWS EC2.

## Technologies Used
- AWS EC2
- Ubuntu Server
- Docker
- Nginx
- HTML and CSS
- Git and GitHub

## Project Structure
- index.html: Web application
- Dockerfile: Instructions to build the Docker image
- README.md: Project documentation

## Build the Docker Image
docker build -t devops-containerized-app:1.0 .

## Run the Container
docker run -d --name devops-web -p 8081:80 devops-containerized-app:1.0

## Access the Application Locally
When running the Docker container on your own computer:

http://localhost:8081

## AWS Deployment

The application is deployed on an AWS EC2 instance and is publicly accessible at:

http://13.206.143.59:8081

The application runs inside a Docker container using Nginx and is accessible on port 8081.


## Author
Hrushik 
