## 🧱 Project Structure

This project is a **full-stack application** organized into three main components:

---

### 📦 Backend (`/backend`)
- Built with **FastAPI (Python)**  
- Runs on **Uvicorn** as the ASGI server  
- Uses a local **SQLite database (`tasks.db`)**  
- Includes **Dockerfile** for containerization  

---

### 💻 Frontend (`/frontend`)
- Developed using **React (JavaScript)**  
- Bootstrapped with **Create React App (react-scripts)**  
- Contains **Nginx configuration (`nginx.conf`)**  
- Includes **Dockerfile** for serving static files  

---

### ☸️ Infrastructure (`/k8s`)
- Holds **Kubernetes manifests** for deploying both frontend and backend  
- Designed for container orchestration and scalability  

---

## ⚙️ Tech Stack
- **Languages:** Python (Backend), JavaScript (Frontend)  
- **Frameworks:** FastAPI, React  
- **Database:** SQLite  
- **DevOps Tools:** Docker, Kubernetes  

---
