# api-rest

### [1. Understand the fundamentals of the Web](https://github.com/KleberVales/api-rest/wiki/01-Understand-the-fundamentals-of-the-Web)

- What is HTTP (web protocol)
- Main methods: GET, POST, PUT, DELETE, PATCH
- Status codes (200 OK, 404 Not Found, 500 Internal Server Error)
- Structure of a request: URL, headers, body, response

### [2. REST concept](https://github.com/KleberVales/api-rest/wiki/02-REST-concept)

- REST = Representational State Transfer
- Principles:
     - Resources represented by URLs (e.g., /clients/1)
     - Stateless: each request is independent
     - Correct use of HTTP verbs
     - Data format: typically JSON

 ### [3. Tools for practice](https://github.com/KleberVales/api-rest/wiki/03-Tools-for-practice)

 - Postman or Insomnia → for testing APIs
 - curl → command line for HTTP requests

### [4. Complete CRUD](https://github.com/KleberVales/api-rest/wiki/04-Complete-CRUD)

- Create endpoints for Create, Read, Update, Delete
- Using Spring Data JPA for database persistence (e.g., PostgreSQL)

### [5. Good practices](https://github.com/KleberVales/api-rest/wiki/05-Good-practices)

- Structure URLs clearly (/clients/{id}/orders)
- Use the correct status codes
- Return standardized error messages
- Document the API using Swagger/OpenAPI

### [6. Advanced features](https://github.com/KleberVales/api-rest/wiki/06-Advanced-features)

- Authentication and authorization (JWT, OAuth2, Spring Security)
- Pagination and filters in endpoints
- API versioning (/v1/clients)
- HATEOAS (links within the answers)

### [7. Integration with other technologies](https://github.com/KleberVales/api-rest/wiki/07-Integration-with-other-technologies)

- Kafka → REST APIs can publish events
- Docker/Kubernetes → package and scale APIs
- Cloud (AWS/OCI) → deployment in real-world environments




