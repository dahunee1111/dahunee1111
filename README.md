# 👋 Dahun Jeon

## 🌐 Personal Portfolio Website

https://dahunee1111.github.io/Main/index.html

> AI Developer | Building Real-World AI Systems  
> AI · Backend · Computer Vision · Deployment · Problem Solving · System Development

---

# 🧠 About Me

I am focused on building real-world AI systems, not just studying AI models.

Currently, I am developing:

- AI-powered developer support systems
- Real-time CCTV danger detection systems
- AI behavior analysis pipelines
- Backend APIs and integrated service architectures
- Docker-based deployment environments
- Cloud-based AI service operations

I am especially interested in:

- AI system engineering
- Computer Vision
- Backend API architecture
- Automation systems
- AI-based monitoring & response systems
- End-to-end service development
- Docker & cloud deployment

From AI model integration to backend APIs, frontend connections, deployment, and system operation,  
I aim to build complete working AI services.

---

# 🚀 Featured Projects

---

# 🤖 AI Developer Assistant

> AI-powered developer learning, code analysis, and chatbot support platform

An AI-based web platform designed to support developer learning, error analysis, code review, study tracking, learning visualization, and real-time chatbot interaction.

This project was built as a fullstack AI service with:

- FastAPI backend API
- GitHub Pages frontend
- SQLite database
- JWT authentication
- Hugging Face API-based AI response flow
- Floating AI chatbot assistant
- Rule-based fallback response system
- Docker-based backend environment
- AWS EC2 server deployment
- DuckDNS domain connection

---

## 🔥 Main Features

- 🧠 AI-based error analysis and solution guidance
- 💻 Code review and improvement suggestions
- 🤖 Floating AI chatbot for project, Python, FastAPI, and deployment questions
- 💬 User-specific chatbot conversation history
- 🛡 Rule-based fallback chatbot responses when AI API is unavailable
- 📚 Learning journal & study tracking
- 📅 Attendance system with learning day calculation
- 💰 Log-based point reward system
- 🛒 Shop system with profile customization
- 📊 Learning data visualization
- 🔐 JWT-based authentication system
- 👨‍💼 Admin management system

---

## ⚙️ Tech Stack

### Backend

- Python
- FastAPI
- SQLite
- SQLAlchemy
- Pydantic
- JWT / python-jose

### Frontend

- HTML
- CSS
- JavaScript
- Chart.js

### AI

- Hugging Face Inference API
- Project-aware AI chatbot
- Rule-based fallback response
- AI error analysis prompt flow
- Code review prompt flow

### Deployment

- Docker
- AWS EC2
- DuckDNS
- GitHub Pages

---

## 🧩 Architecture

```text
Client UI (GitHub Pages)
        ↓
Floating Chatbot UI / Service Pages
        ↓
Backend API (FastAPI + AWS EC2 + DuckDNS)
        ↓
AI Analysis / Chatbot / Service Logic
        ↓
SQLite Database
        ↓
Learning Visualization & History System
```

---

## 🌐 Deployment

```text
User Browser
        ↓
GitHub Pages Frontend
        ↓
https://dahun-ai.duckdns.org
        ↓
AWS EC2 Server
        ↓
Docker Container
        ↓
FastAPI Backend
        ↓
SQLite Database
```

---

## 💡 Key Implementation

### Log-Based Point System

All points are stored as logs and calculated dynamically using SUM queries for scalable structure design.

### Learning Day Tracking

Attendance records and study journal data are combined to calculate actual learning continuity.

### JWT Authentication

Implemented login authentication using JWT and connected user state management with frontend localStorage.

### Floating AI Chatbot Integration

Implemented a floating chatbot UI fixed to the bottom-right side of the website, allowing users to ask questions from any main page without moving to a separate screen.

The chatbot is connected to the FastAPI `/chat` API and supports:

- project explanation
- technology stack guidance
- EC2 / Docker deployment explanation
- Python and FastAPI questions
- error-solving workflow guidance
- user-specific conversation history storage
- fallback responses when the AI API is unavailable
- fixed project information such as the developer name and service structure

### Docker-Based Backend Operation

The backend is operated inside a Docker container on AWS EC2.  
The SQLite database is mounted from the EC2 host to the container to preserve service data during rebuilds and redeployments.

### Full Deployment Experience

Built and deployed a complete AI web service including frontend, backend, database, AI integration, Docker environment, AWS EC2 server operation, DuckDNS domain connection, and GitHub Pages frontend deployment.

---

## 🌐 Live Project

Frontend  
https://dahunee1111.github.io/AI-Developer-Assistant/

Backend API  
https://dahun-ai.duckdns.org

---

# 🚨 AI CCTV Behavior & Danger Detection System

> AI-powered real-time CCTV monitoring & danger response system  
> Team Project

An integrated AI surveillance system designed for real-time abnormal behavior detection, dangerous object detection, risk score calculation, and automated response workflows.

This project combines:

- MediaPipe Pose behavior analysis
- LSTM-based abnormal behavior detection
- YOLO-based dangerous object detection
- FastAPI backend API
- Admin monitoring dashboard
- Discord danger alert system
- RAG-based response guide
- Docker + Render deployment

---

## 🔥 Main Features

- 🎥 Real-time CCTV video analysis
- 🧠 LSTM-based abnormal behavior detection
- 🦴 MediaPipe Pose behavior analysis
- 🔪 YOLO-based dangerous object detection
- ⚠️ AI risk score calculation system
- 🚨 Discord real-time danger alert system
- 📚 RAG-based response guide system
- 👨‍💼 Admin monitoring dashboard
- 📊 Risk statistics visualization
- 📹 CCTV registration & management
- 🗂 Analysis history system

---

## ⚙️ Tech Stack

### Backend

- Python
- FastAPI
- SQLite
- SQLAlchemy

### AI / Computer Vision

- PyTorch
- YOLO
- OpenCV
- MediaPipe Pose
- NumPy
- LSTM

### Frontend

- HTML
- CSS
- JavaScript
- Chart.js

### Notification

- Discord Webhook

### Deployment

- Docker
- Render
- GitHub

---

## 🧩 AI Pipeline

```text
Video Input
        ↓
Behavior Analysis (MediaPipe + LSTM)
        ↓
Dangerous Object Detection (YOLO)
        ↓
Risk Score Calculation
        ↓
Response Decision
        ↓
Discord Alert
        ↓
RAG Response Guide
        ↓
Database Storage
        ↓
Admin Dashboard Visualization
```

---

## 🌐 Deployment

```text
User Browser
        ↓
Render Web Service
        ↓
Docker Container
        ↓
FastAPI Backend
        ↓
AI Analysis Pipeline
        ↓
SQLite Database
        ↓
Admin Dashboard / Alert System
```

---

## 💡 Project Goal

This project aims to move beyond simple object detection and create a real AI monitoring system capable of:

- understanding dangerous situations,
- calculating risk levels,
- generating response actions,
- sending real-time danger alerts,
- supporting admin monitoring workflows.

---

## 🌐 Live Project

https://ai-behavior-system.onrender.com/

---

# ⚙️ Overall Technical Experience

## 🧩 Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## 🌐 Frontend

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## ⚙️ Backend & AI

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)  
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)  
![YOLO](https://img.shields.io/badge/YOLO-111111?style=for-the-badge)  
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)  
![MediaPipe](https://img.shields.io/badge/MediaPipe-FF6F00?style=for-the-badge)  
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)  
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

---

## 🛠 Tools & Environment

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)  
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)  
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)  
![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge)  
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

---

# 🌐 Portfolio

## Portfolio Website

https://dahunee1111.github.io/Main/index.html

---

# 🚀 Future Goals

- Build scalable AI monitoring systems
- Improve real-time AI analysis pipelines
- Develop production-level AI backend systems
- Expand AI + automation integrated services
- Improve Docker-based deployment environments
- Expand AWS EC2 / Render cloud operation experience
- Create complete AI service architectures from model to deployment
- Improve project-aware chatbot response quality
- Build personalized AI learning feedback features

---

# 📬 Contact

- Email: dahunee1111@naver.com
- GitHub: https://github.com/dahunee1111
- Portfolio: https://dahunee1111.github.io/Main/index.html

---

# 🚀 Growth Philosophy

> From learning → building  
> From ideas → real systems  
> From local code → deployed AI services

---

# 📄 License

This profile README is for portfolio and educational purposes.
