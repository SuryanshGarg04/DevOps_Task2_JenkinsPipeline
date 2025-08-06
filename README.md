# 🚀 DevOps Task 2: Jenkins Pipeline Integration

This project demonstrates a basic CI/CD pipeline using **Jenkins**, integrated with a **Node.js + Express** Dockerized web application.

## 📁 Project Structure

├── app.js
├── Dockerfile
├── Jenkinsfile
├── package.json
├── package-lock.json
├── public/
├── src/
├── templates/

## 🔧 Technologies Used

- Node.js
- Express.js
- Docker
- Jenkins
- GitHub

## 🧪 Jenkins Pipeline Stages

The Jenkins pipeline (`Jenkinsfile`) consists of the following stages:

1. **Build** – Echoes a placeholder build step.
2. **Test** – Runs mock test scripts or echo command.
3. **Deploy** – Echoes deploy step (can be replaced with actual deployment logic).

## 🐳 Docker

A `Dockerfile` is included to containerize the application.

### Build Docker Image

```bash
docker build -t my-node-app 
```
### Run Docker Container
docker run -p 3000:3000 my-node-app
### 📦 How to Run Locally
npm install
node app.js
Then open http://localhost:3000 in your browser.

