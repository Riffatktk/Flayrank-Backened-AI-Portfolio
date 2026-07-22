# BE-04 – Containerize Your Stack

## Assignment Overview

This assignment was completed as part of the **Backend Engineering** specialization during the **FlyRank AI Internship (July 2026 Cohort)**.

The objective was to containerize a backend application using Docker and connect it to a PostgreSQL database. The project demonstrates how the application can switch between different storage implementations without changing the API routes or business logic.

---

## Objectives

- Containerize the backend application using Docker.
- Connect the application with a PostgreSQL database.
- Implement the Repository Pattern for data access.
- Keep the application architecture modular and maintainable.
- Verify that application data remains available after restarting containers.

---

## Technologies Used

- Python
- FastAPI
- PostgreSQL
- Docker
- Docker Compose
- Git & GitHub

---

## Project Structure

This assignment includes:

- `main.py`
- `repository.py`
- `docker-compose.yml`
- `init.sql`
- `requirements.txt`
- `README.md`

---

## Running the Project

```bash
docker compose up
```

After the containers start successfully, the application is available at:

```
http://localhost:8000
```

---

## Testing

Example API requests:

```bash
curl -X POST http://localhost:8000/items
```

```bash
curl http://localhost:8000/items
```

---

## Expected Outcome

The backend application should:

- Start successfully using Docker.
- Connect to the PostgreSQL database.
- Store and retrieve data correctly.
- Preserve data after restarting containers.

---

## Screenshots

Screenshots demonstrating successful execution will be added after completing the assignment.

---

## Learning Outcomes

Through this assignment, I learned how to:

- Build containerized backend applications.
- Work with Docker and Docker Compose.
- Connect FastAPI to PostgreSQL.
- Apply the Repository Pattern for clean architecture.
- Organize backend projects using professional development practices.

---

## Status

🚧 In Progress

---

**Author**

**Riffat **

BS Computer Science Student


FlyRank AI Internship – July 2026 Cohort
