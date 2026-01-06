# finalproject
Project Description
This project is Task 2 for the Spring Framework Apps assignment. The goal of this task is to create
a fully functional REST API using Spring Boot. The application supports CRUD operations,
exception handling, Swagger documentation, and an in-memory H2 database.
Technologies Used
• Java
• Spring Boot
• Spring Web (REST)
• Spring Data JPA
• H2 Database
• Swagger / OpenAPI
• Maven
How to Run the Application
1. Open the project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run Project2Application.java
4. Application runs on port 8080
API Endpoints
POST /api/v1/products – create product
GET /api/v1/products/{id} – get product by id
GET /api/v1/products – get all products<img width="2188" height="1333" alt="Screenshot 2025-12-22 172819" src="https://github.com/user-attachments/assets/b8fc8702-5da1-43e4-b495-6b524bfe0b81" />

PUT /api/v1/products/{id} – update product<img width="2263" height="1421" alt="Screenshot 2025-12-22 172737" src="https://github.com/user-attachments/assets/351d7cd8-4f9f-4cc7-b63e-cf4b308ca6d4" />

DELETE /api/v1/products/{id} – delete product
H2 Database
URL: http://localhost:8080/console
JDBC URL: jdbc:h2:mem:testdb
User: sa
Password: (empty)
Swagger UI
URL: http://localhost:8080/swagger-ui/index.html
Application Architecture
Controller – handles HTTP requests
Service – business logic
Repository – database access using JPA
Mapper – maps request and response objects
Exception Handling
Custom exception handling is implemented using @ControllerAdvice. When a product is not found,
the API returns HTTP 404 with a descriptive error message<img width="1245" height="878" alt="Screenshot 2026-01-06 220956" src="https://github.<i<img width="1212" height="724" alt="Screenshot 2026-01-06 221145" src="https://github.com/user-attachments/assets/873934ba-a9ee-4158-a4a6-5517a4d2b9c1" />
mg width="999" height="514" alt="Screenshot 2026-01-06 221125" src="https://github.com/user-attachments/assets/3cdd6805-927a-43d6-a47d-1d01ebb7d19b" />
<img width="1377" height="782" alt="Screenshot 2026-01-06 221051" src="https://github.com/user-attachments/assets/b8af6e5a-4ec6-4403-9410-469708829097" />
com/user-attachments/assets/07e61398-d637-4fb7-b709-47fa402cb183" /><img width="1239" height="891" alt="Screenshot 2026-01-06 221036" src="https://github.com/user-attachments/assets/a92189e5-1279-4703-833d-dc9a5e4104ec" />


<img width="1278" height="924" alt="Screenshot 2026-01-06 220941" src="https://github.com/user-attachments/assets/dd712513-9374-4f98-8372-c4a0bea5b67c" />
