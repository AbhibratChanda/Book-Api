Book Management API
A simple CRUD API built using Java Spring Boot and MySQL.

🧪 API Endpoints

| Method | Endpoint             | Description            |
|--------|----------------------|------------------------|
| GET    | `/api/books`         | Get all books          |
| GET    | `/api/books/{id}`    | Get a book by ID       |
| POST   | `/api/books`         | Add a new book         |
| PUT    | `/api/books/{id}`    | Update an existing book|
| DELETE | `/api/books/{id}`    | Delete a book by ID    |


How to Run
Create a MySQL database named bookdb
Update DB credentials in application.properties

Run the app:
mvn spring-boot:run

