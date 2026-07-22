# BE-01 – Build Your First API Endpoint

## Assignment Overview

This assignment was completed as part of the **Backend Engineering** specialization during the **FlyRank AI Internship (July 2026 Cohort)**.

The goal was to build a simple backend application using **FastAPI** that exposes two basic JSON endpoints and to verify that they work correctly through both a web browser and command-line requests.

---

## Objectives

- Build a basic FastAPI application.
- Create two JSON API endpoints.
- Run the application locally using Uvicorn.
- Test API responses using both a browser and `curl`.
- Understand the fundamentals of HTTP request and response handling.

---

## Technologies Used

- Python
- FastAPI
- Uvicorn
- Git & GitHub

---

## Project Files

This folder contains:

- `main.py`
- `requirements.txt`
- `README.md`
- Screenshots showing successful execution

---

## How to Run

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

---

## Testing the API

### Browser

```
http://127.0.0.1:8000/
http://127.0.0.1:8000/status
```

### Using curl

```bash
curl http://127.0.0.1:8000/
curl http://127.0.0.1:8000/status
```

---

## Output

The application returns successful JSON responses from both endpoints, confirming that the backend server is running correctly.

---

## Screenshots

The following screenshots demonstrate:

- FastAPI server running successfully.
- Root endpoint response.
- Status endpoint response.

*(Screenshots will be added in the `Screenshots` folder.)*

---

## Learning Outcomes

Through this assignment, I learned how to:

- Build a basic REST API using FastAPI.
- Start a local development server with Uvicorn.
- Test API endpoints using different methods.
- Organize backend project files in a professional GitHub repository.

---

## Status

✅ Completed

---

**Author**

**Riffat **

BS Computer Science Student


FlyRank AI Internship – July 2026 Cohort
