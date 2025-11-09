# Growly Infra

Central hub for the **Growly** microservices architecture — a habit tracking system with user management, activity analysis, and scalable design.

## 📌 Architecture

This project consists of the following microservices:

| Service                | Description                                     | Link |
|------------------------|-------------------------------------------------|------|
| `growly-api-gateway`   | API Gateway built with Spring Cloud Gateway     | [api-gateway](https://github.com/LPF-24/growly-api-gateway) |
| `growly-auth-service`  | Handles authentication and authorization (JWT) | [auth-service](https://github.com/LPF-24/growly-auth-service) |
| `growly-habit-service` | Manages user habits                            | [habit-service](https://github.com/LPF-24/growly-habit-service) |
| `growly-main-ui`       | User profile management                        | [main-ui](https://github.com/LPF-24/growly-main-ui) |
| `growly-notification-service` | Habit reminders and notifications              | [notification-service](https://github.com/LPF-24/growly-notification-service) |

Infrastructure services:

- [`growly-infra`](https://github.com/LPF-24/growly-infra) — centralized configuration service
- [`growly-eureka-server`](https://github.com/LPF-24/growly-eureka-server) — service discovery via Netflix Eureka

## 🐳 Running the Stack with Docker Compose

```bash
docker compose up -d --build 
```

## 👥 Sample Accounts (http://localhost:5173/login)

| Role  | Username | Password   |
|-------|----------|------------|
| Admin | `admin`  | `ChangeMe_123!` |
| User  | `user`   | `user123!` |

Make sure to configure the `.env` file with appropriate environment variables (e.g. PostgreSQL, JWT secrets).

## 🧰 Tech Stack

- Java 17  
- Spring Boot  
- Spring Cloud  
- PostgreSQL  
- Redis  
- Kafka  
- Docker & Docker Compose  
- Eureka  
- OpenAPI (Swagger)  
- Maven  
- JWT
- JUnit 5
- Mockito

## 📌 Project Status

🚀 The system is up and running.  
🧪 Test coverage (unit/integration) is being actively developed.  
📚 Some documentation and infrastructure aspects are still under improvement.

## 📚 Documentation

Each microservice contains its own `README.md` with setup instructions and API reference.  
**REST APIs** are documented via **OpenAPI (Swagger)**.

## 👤 Author

**LPF-24** — aspiring Java backend developer building real-world projects with Spring, REST APIs, and Docker.

GitHub: [@LPF-24](https://github.com/LPF-24)

---

> 🌱 **Growly** — more than a habit tracker. It's a system for sustainable growth.
