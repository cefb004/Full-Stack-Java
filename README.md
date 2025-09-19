This project is a **modern full stack web application** built with **Spring Boot (Java)** on the backend, **Angular (TypeScript)** on the frontend, and **PostgreSQL** as the relational database. The entire solution is containerized with **Docker**, ensuring easy deployment and scalability across environments.

## 🔹 Key Features

### Backend (Spring Boot)
- Exposes a set of **RESTful APIs** to handle CRUD operations.
- Uses **Spring Data JPA** to interact with PostgreSQL in a clean and efficient way.
- Integrates **Flyway** for database migrations and version control.
- Implements **validation and error handling** using Spring Boot features.

### Frontend (Angular)
- Provides a **modern single-page application (SPA)** interface.
- Consumes the backend APIs to display and manage data.
- Uses **Reactive Forms** and **HTTP Client** for seamless integration with the backend.
- Designed with **Bootstrap / Material** for responsive and user-friendly UI.

### Database (PostgreSQL)
- Stores application data in a relational schema.
- Managed and versioned using **Flyway migrations**.
- Runs in a Docker container for portability and consistency.

### Deployment (Docker + Docker Compose)
- Backend, frontend, and database are all containerized.
- Docker Compose orchestrates services, making it easy to start the entire application with a single command.
- Ensures the project can run consistently on any machine, regardless of local environment setup.

## 🔹 Project Flow
1. **Frontend (Angular)** → The user interacts with a modern web interface.  
2. **Backend (Spring Boot)** → Angular calls the REST API to request or persist data.  
3. **Database (PostgreSQL)** → The backend queries and updates the relational database.  
4. **Flyway Migrations** → Automatically manage database schema changes.  
5. **Docker** → Everything runs inside isolated containers for simplicity.  

## 🔹 Example Use Case
A **Person Management System** where users can:
- Create a new person (name + email).
- List all registered people.
- Delete a person by ID.

This use case demonstrates the **end-to-end integration** of Angular, Spring Boot, and PostgreSQL.

---

✅ With this setup, the project provides a **solid foundation for building scalable enterprise applications**, following industry best practices for **full stack Java development**.
