# Workture

**Workture** is a backend job portal application built using **Java Spring Boot** following a **microservices architecture**. It provides core features such as user registration, job posting, job search, and application handling. The project is modular, scalable, and built with industry-standard practices.

---

## 🛠️ Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- Spring Web
- Spring Security
- Spring Cloud (for service discovery)
- MySQL / H2 (for local development)
- Docker (optional)
- Git & GitHub for version control
- Maven / Gradle
- Lombok

---

## ✨ Features (To Be Built)

- ✅ User Registration & Login
- 🔐 Secure endpoints using JWT (planned)
- 📄 Post, update, and delete job listings
- 🔎 Search and filter jobs by keyword/location/type
- 📤 Apply to job postings
- 📊 Admin dashboard (planned)
- 📦 Containerized deployment with Docker (optional)

---

## 🚀 Getting Started

### Prerequisites

- Java 17 or above
- Maven
- MySQL or H2 (for dev)
- IDE (IntelliJ, Eclipse, VSCode)

### Steps

1. Clone the repo:

```bash
git clone https://github.com/Ajay3136/workture.git
cd workture
Build the project:


./mvnw clean install
Run the application:


./mvnw spring-boot:run
Access API locally:


http://localhost:8080/api/
🔧 Configuration
application.properties example:


spring.datasource.url=jdbc:mysql://localhost:3306/workture_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
Use H2 for easy testing:


spring.datasource.url=jdbc:h2:mem:workture
spring.h2.console.enabled=true
📚 Future Plans
Job Recommendation System

Resume Parsing with ML

Microservice deployment on Kubernetes

API Gateway & Service Discovery (Eureka/Consul)

🤝 Contributing
Want to contribute? Open an issue or fork the repo and submit a pull request!
