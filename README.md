# Containerised CRUD REST API
---

## 📌 Project Description
This project is a fully containerised REST API that provides complete CRUD (Create, Read, Update, Delete) functionality. It is built using Node.js and Express, with PostgreSQL as the database and Nginx acting as a reverse proxy.

Each service runs in its own Docker container and is managed efficiently using Docker Compose.

---

## 🚀 Tech Stack
- Node.js + Express (Backend API)
- PostgreSQL (Database)
- Nginx (Reverse Proxy)
- Docker + Docker Compose (Containerisation)

---

## ⚙️ How to Run the Project
```bash
cp .env.example .env
docker compose up --build -d
