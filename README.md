# Docker Hands-On Guide 🐳

## ✅ Hands-On Tasks

### 🔁 Understand Container Lifecycle
- Start container:
  ```bash
  docker start <container_id>
  ```
- Stop container:
  ```bash
  docker stop <container_id>
  ```
- Remove container:
  ```bash
  docker rm <container_id>
  ```
- Remove image:
  ```bash
  docker rmi <image_id>
  ```

### 📦 Basic Docker Commands
- List running containers:
  ```bash
  docker ps
  ```
- List all containers:
  ```bash
  docker ps -a
  ```

### 🖼️ Working with Images
- Pull image from Docker Hub:
  ```bash
  docker pull nginx
  ```
- Run container from image:
  ```bash
  docker run -d -p 8080:80 nginx
  ```
- List images:
  ```bash
  docker images
  ```

### 🛠 Understanding Dockerfile
- Write a Dockerfile for Node.js or Python app
- Build image:
  ```bash
  docker build -t myapp .
  ```
- Run the custom image:
  ```bash
  docker run -d -p 5000:5000 myapp
  ```

### 🏆 Mini-Project: Simple Node.js App in Docker
- 🌐 Create a simple web app
- 📝 Write a Dockerfile
- 🔧 Build and run it in a container

---

