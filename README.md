# HMCTS Tasks Backend

Spring Boot REST API for managing caseworker tasks.

## Running locally

1. Start Postgres:

```bash
docker compose up -d
```

2. Run the API:

```bash
mvn spring-boot:run
```

API will be available at `http://localhost:8080`.

Swagger UI: `http://localhost:8080/swagger-ui.html`

## Tests

```bash
mvn test
```
