# Task Manager Backend

Spring Boot REST API for managing tasks with clean architecture using DTOs, validation, filtering and global exception handling.

---

## Features

- CRUD operations for tasks
- DTO architecture
- Validation using Jakarta Validation
- Global exception handling
- Filtering by status and priority
- H2 in-memory database
- RESTful API design

---

## Tech Stack

- Java 17
- Spring Boot
- Spring Data JPA
- Maven
- H2 Database
- Jakarta Validation

---

## API Endpoints

### Create Task
POST /tasks

### Get All Tasks
GET /tasks

### Get Task by ID
GET /tasks/{id}

### Update Task
PUT /tasks/{id}

### Delete Task
DELETE /tasks/{id}

### Filter Tasks
GET /tasks?status=TODO  
GET /tasks?priority=HIGH  

---

## Example Request

## Example Request

```json
{
  "title": "Learn Spring Boot",
  "description": "Build REST API",
  "status": "TODO",
  "priority": "HIGH"
}
```

---

## Project Structure

controller → REST API endpoints  
service → Business logic  
repository → Database interaction  
entity → Database models  
dto → Request / response objects  
exception → Global exception handling  

---

## Future Improvements

- Pagination support  
- MySQL / PostgreSQL database integration  
- Swagger API documentation  
- JWT authentication  
- Docker containerization  

---

## Author

Kedarieshwar Krishna Gadasu
