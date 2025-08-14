# Distributed Chat Application

A **real-time, full-stack messaging platform** built with **Java (Spring Boot)** for the backend and **React + WebSockets (STOMP)** for the frontend.  
This application demonstrates **distributed systems design**, **full-stack development**, **debugging**, and **production-ready deployment**.  

Designed to support **10,000+ concurrent users** with **low-latency communication**, **end-to-end encryption**, and **scalable architecture**.

---

## 📌 Features
- **Real-Time Messaging** – Instant, low-latency text communication using WebSockets.
- **End-to-End Encryption** – Secure message transfer between clients.
- **Scalable Architecture** – Supports thousands of concurrent connections with minimal latency.
- **Monitoring & Debugging** – Integrated Prometheus and Grafana for performance and system health monitoring.
- **Full-Stack Implementation** – Java backend with WebSocket API + React frontend UI.
- **Version Control & CI/CD Ready** – Git-based workflow with test coverage.
- **Unit Testing** – Backend tested using JUnit.

---

## 🛠 Tech Stack

**Backend**
- Java 17
- Spring Boot
- WebSocket (STOMP Protocol)
- Maven Build Tool
- JUnit (Testing)

**Frontend**
- React
- JavaScript (ES6+)
- HTML5, CSS3
- WebSocket Client Library

**DevOps / Tools**
- Git & GitHub
- Prometheus & Grafana (Monitoring)
- CI/CD Ready (GitHub Actions)

---
## 📂 Project Structure
distributed-chat-app/
│
├── backend/ # Spring Boot backend
│ ├── src/main/java/... # Java source code
│ ├── src/main/resources # Config files
│ └── pom.xml # Maven dependencies
│
├── frontend/ # React + WebSocket frontend
│ ├── index.html # Main entry point
│ ├── static/js # Client scripts
│ └── styles/ # UI styling
│
└── README.md # Project documentation

Installation & Setup

Tell people exactly how to run the project locally (backend and frontend).
Example:

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/vallurun/distributed-chat-app.git
cd distributed-chat-app

2. Run Backend
cd backend
mvn spring-boot:run


Backend runs on http://localhost:8080
WebSocket endpoint: /ws-chat

3. Run Frontend

Open frontend/index.html in your browser.


---

### **2️⃣ Testing**
If you have tests, mention them:  
```markdown
## 🧪 Testing
To run backend tests:
```bash
cd backend
mvn test


---


## 📂 Project Structure
