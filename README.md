# TimiNow
REST API for discovering and managing events in Cluj-Napoca. Built with Java 21, Spring Boot, PostgreSQL and JWT authentication.


# TimiNow API

A RESTful backend for discovering and managing events in Timisoara.
Users can browse events, filter them by category and date, and, once
registered, create and manage their own events.

## Features

- CRUD operations for events
- User registration and login with JWT authentication
- Only the author of an event can edit or delete it
- Filtering by category and date range, with pagination
- Input validation and centralized error handling
- Interactive API documentation with Swagger UI

## Tech Stack

- **Language:** Java 21
- **Framework:** Spring Boot, Spring Web, Spring Data JPA
- **Security:** Spring Security, JWT, BCrypt
- **Database:** PostgreSQL
- **Testing:** JUnit 5, Mockito, MockMvc
- **Documentation:** springdoc-openapi (Swagger UI)
- **DevOps:** Docker, Docker Compose, GitHub Actions

## Getting Started

1. Clone the repository
2. Run `docker compose up`
3. Open Swagger UI at `http://localhost:8080/swagger-ui.html`

## Project Structure

Layered architecture: controller → service → repository,
with separate DTOs, security and exception-handling packages.
