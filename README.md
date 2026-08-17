# SmartFleet Demo API (Spring Boot)

A small REST API for managing companies, built to practice backend development in Java/Spring Boot — a companion project to [SmartFleet API](https://github.com/saraflehi/smartfleet-api), which is built in Python/FastAPI.

## Stack
- Java 17
- Spring Boot 4.1
- Spring Data JPA / Hibernate
- PostgreSQL

## Endpoints
| Method | Endpoint                    | Description              |
|--------|------------------------------|---------------------------|
| GET    | `/api/v1/companies`          | List all companies        |
| GET    | `/api/v1/companies/{id}`     | Get a single company      |
| POST   | `/api/v1/companies`          | Create a new company      |

## Running locally
1. Create a PostgreSQL database
2. Update `src/main/resources/application.properties` with your database credentials
3. Run: ./mvnw spring-boot:run
4. API available at `http://localhost:8080`
  
