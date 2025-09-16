# FinTrust – Loan & Credit Approval System (Full Stack)

A full-stack microservices project simulating a real-world loan & credit approval platform.

## 🔹 Tech Stack
- **Backend:** Java 17, Spring Boot 3, PostgreSQL, RabbitMQ, Docker, Swagger (OpenAPI)
- **Frontend:** React, Vite, TypeScript
- **DevOps:** Docker Compose, GitHub Actions (optional)

## 🔹 Architecture
- Loan Service (8081) → Accepts loan applications, publishes events
- Credit Service (8082) → Listens, performs credit checks, returns decisions
- Notification Service (8083) → Stores notifications based on decisions
- Frontend (5173) → User applies for loan, checks decision, views notifications

## 🔹 Demo
- Backend Repo 👉 [fintrust-backend](https://github.com/KrishnaVarmaAyinampudi/fintrust-backend)
- Frontend Repo 👉 [fintrust-frontend](https://github.com/KrishnaVarmaAyinampudi/fintrust-frontend)

## 🔹 How to Run
1. Clone backend and run:
   ```bash
   docker compose up --build
