# Growly Infra

Central hub for the **Growly** microservices architecture — a habit tracking system with user management, activity analysis, and scalable design.

## 📌 Architecture

This project consists of the following microservices:

| Service                | Description                                     | Link |
|------------------------|-------------------------------------------------|------|
| `growly-api-gateway`   | API Gateway built with Spring Cloud Gateway     | [Link](https://github.com/LPF-24/growly-api-gateway) |
| `growly-auth-service`  | Handles authentication and authorization (JWT) | [Link](https://github.com/LPF-24/growly-auth-service) |
| `growly-habit-service` | Manages user habits                            | [Link](https://github.com/LPF-24/growly-habit-service) |
| `growly-main-ui`       | User profile management                        | [Link](https://github.com/LPF-24/growly-main-ui) |
| `growly-notification-service` | Habit reminders and notifications              | [Link](https://github.com/LPF-24/growly-notification-service) |

Infrastructure services:

- `growly-infra` — centralized configuration service
- `growly-eureka-server` — service discovery via Netflix Eureka

## 🐳 Running the Stack with Docker Compose

```bash
docker compose up --build
```

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

## 🤝 Contributing

Pull requests are welcome!  
Please follow the code style, include tests, and update relevant documentation.

---

> 🌱 **Growly** — more than a habit tracker. It's a system for sustainable growth.
