# 🌐 CodeAlpha Web Server Using Docker

A simple Dockerized web server project developed as part of the CodeAlpha DevOps Internship. This project demonstrates how to deploy a static website inside a Docker container using Nginx, helping understand the fundamentals of containerization and web server deployment.

---

## 📌 Project Objective

The goal of this project is to:

- Learn Docker containerization basics
- Deploy a web server using Docker
- Understand Docker images and containers
- Manage container lifecycle
- Explore web application deployment using Nginx

---

## 🛠️ Technologies Used

- Docker
- Nginx
- HTML
- GitHub

---

## 📂 Project Structure

```text
CodeAlpha_WebServer_Docker/
│
├── screenshots/
│   └── page.png
│
├── Dockerfile
├── README.md
└── index.html
```

---

## 📄 Application Code

### index.html

```html
<!DOCTYPE html>
<html>
<head>
    <title>CodeAlpha Docker Project</title>
</head>
<body>
    <h1>Docker Web Server Running Successfully</h1>
    <p>CodeAlpha DevOps Internship Task</p>
</body>
</html>
```

---

## 🐳 Dockerfile

```dockerfile
FROM nginx:latest

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80
```

---

## 🚀 How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/your-username/CodeAlpha_WebServer_Docker.git
cd CodeAlpha_WebServer_Docker
```

### 2. Build Docker Image

```bash
docker build -t codealpha-webserver .
```

### 3. Run Docker Container

```bash
docker run -d -p 8080:80 codealpha-webserver
```

### 4. Open in Browser

```text
http://localhost:8080
```

---

## ✅ Expected Output

```text
Docker Web Server Running Successfully

CodeAlpha DevOps Internship Task
```

---


## 🎯 Learning Outcomes

- Docker installation and setup
- Creating Docker images
- Running Docker containers
- Port mapping in Docker
- Deploying static websites using Nginx
- Understanding containerized applications

---

## 👨‍💻 Author

**Kartik Gupta**

DevOps Intern – CodeAlpha

---

## 📜 Internship Task

This project was completed as part of the CodeAlpha DevOps Internship Program.
