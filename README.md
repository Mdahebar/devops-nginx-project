# Dockerized Nginx Web Application Deployment on AWS EC2

## 📌 Project Overview

This project demonstrates how to deploy a custom Nginx web application inside a Docker container on an AWS EC2 Ubuntu server.

The project also uses Git and GitHub for version control and source-code management.

## 🏗️ Architecture

Developer
   |
   v
Git
   |
   v
GitHub
   |
   v
AWS EC2 Ubuntu
   |
   v
Docker Container
   |
   v
Nginx Web Server
   |
   v
Custom Web Application

## 🛠️ Technologies Used

- AWS EC2
- Ubuntu Linux
- Docker
- Nginx
- Git
- GitHub
- HTML

## 📂 Project Structure

```text
devops-nginx-project/
├── Dockerfile
├── index.html
└── README.md


FROM nginx:latest

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80





docker build -t my-devops-nginx .

docker run -d --name my-nginx-app -p 8080:80 my-devops-nginx

curl http://localhost:8080

http://YOUR_EC2_PUBLIC_IP:8080



Working Directory
       |
       | git add
       v
Staging Area
       |
       | git commit
       v
Local Repository
       |
       | git push
       v
GitHub



