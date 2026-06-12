# Docker Static Website Project

## 📌 Project Overview

This project demonstrates how to containerize and deploy a static website using Docker and Nginx on an AWS EC2 instance.

The website is packaged into a Docker image using a Dockerfile and deployed inside a container, making it portable, scalable, and easy to manage across different environments.

---

## 🎯 Objectives

* Understand Docker Images and Containers
* Learn Dockerfile creation and image building
* Deploy a static website using Nginx
* Implement port mapping for external access
* Practice container lifecycle management
* Gain hands-on experience with AWS EC2 and Docker

---

## 🏗️ Project Architecture

User Browser
↓
AWS EC2 Instance
↓
Docker Container
↓
Nginx Web Server
↓
Static Website (index.html)

---

## 🛠️ Technologies Used

* Docker
* Nginx
* Linux (Ubuntu)
* AWS EC2
* Git & GitHub

---

## 📂 Project Structure

docker-static-website/
├── Dockerfile
├── index.html
└── README.md

---

## 📝 Dockerfile

FROM nginx

COPY index.html /usr/share/nginx/html

EXPOSE 80

---

## 🚀 Build Docker Image

docker build -t sahil-website .

---

## ▶️ Run Docker Container

docker run -d --name website-container -p 8080:80 sahil-website

---

## 🔍 Verify Running Container

docker ps

---

## 🌐 Access Website

http://<EC2-PUBLIC-IP>:8080

Example:

http://18.xxx.xxx.xxx:8080

---

## 📚 Key Docker Concepts Learned

### Docker Image

A read-only template containing application code, dependencies, and configurations.

### Docker Container

A running instance of a Docker image.

### Dockerfile

A script containing instructions to build Docker images.

### Port Mapping

Maps container ports to host machine ports.

Example:

-p 8080:80

Host Port → 8080

Container Port → 80

### Container Lifecycle

Create

# Docker Static Website Project

## 📌 Project Overview

This project demonstrates how to containerize and deploy a static website using Docker and Nginx on an AWS EC2 instance.

The website is packaged into a Docker image using a Dockerfile and deployed inside a container, making it portable, scalable, and easy to manage across different environments.

---

## 🎯 Objectives

* Understand Docker Images and Containers
* Learn Dockerfile creation and image building
* Deploy a static website using Nginx
* Implement port mapping for external access
* Practice container lifecycle management
* Gain hands-on experience with AWS EC2 and Docker

---

## 🏗️ Project Architecture

User Browser
↓
AWS EC2 Instance
↓
Docker Container
↓
Nginx Web Server
↓
Static Website (index.html)

---

## 🛠️ Technologies Used

* Docker
* Nginx
* Linux (Ubuntu)
* AWS EC2
* Git & GitHub

---

## 📂 Project Structure

docker-static-website/
├── Dockerfile
├── index.html
└── README.md

---

## 📝 Dockerfile

FROM nginx

COPY index.html /usr/share/nginx/html

EXPOSE 80

---

## 🚀 Build Docker Image

Host Port → 8080
### Container Lifecycle
Start
Stop
Restart
Remove

---
* Kubernetes Deployment

---

## 👨‍💻 Author

Sahil Thube

Learning DevOps through the 90 Days of DevOps Challenge with TrainWithShubham under the guidance of Shubham Londhe Sir (Josh Batch 10).

## 💡 Why Containerization?

Traditional Deployment:

* Install software manually
* Configure dependencies
* Docker Networking
* CI/CD with GitHub Actions
* Environment-specific issues
* Difficult scaling

Docker-Based Deployment:

* Consistent environments
* Faster deployments
* Easy scalability
* Docker Compose
* Multi-Container Applications
* Docker Volumes
* Better resource utilization
* Supports CI/CD pipelines
---

## 🚀 Future Enhancements


---
* GitHub Project Management


## 🏢 Industry Use Cases
* AWS EC2 Integration

* Port Mapping
* Container Management
Docker is widely used for:

* Nginx Deployment
* Microservices Architecture
* Dockerfile
* CI/CD Pipelines
* Docker Images
* Docker Containers
* Cloud Deployments
* Docker Installation
## 🎓 Learning Outcomes

* Kubernetes Workloads
* DevOps Automation

---
* Application Modernization

* PayPal
* Adobe

Companies using Docker include:

* Netflix
* Amazon
* Spotify



Create


Container Port → 80


-p 8080:80

docker build -t sahil-website .
Example:


---

Maps container ports to host machine ports.

## ▶️ Run Docker Container
### Port Mapping


docker run -d --name website-container -p 8080:80 sahil-website

---

## 🔍 Verify Running Container

A script containing instructions to build Docker images.


### Dockerfile

A running instance of a Docker image.
### Docker Container

docker ps


A read-only template containing application code, dependencies, and configurations.

---
### Docker Image


## 📚 Key Docker Concepts Learned
## 🌐 Access Website


---
http://18.xxx.xxx.xxx:8080

http://<EC2-PUBLIC-IP>:8080

