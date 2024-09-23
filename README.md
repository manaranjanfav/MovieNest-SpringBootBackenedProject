# MovieAPI - Spring Boot Backend
This project is a MovieAPI built using Spring Boot. It provides programmatic access to a wide variety of movie-related data with industrial-level concepts, including database configurations, file handling, authentication, and more. The API is designed for developers and consumers to interact with movies' data securely and efficiently.

Features
1. CRUD Operations
Create, Read, Update, and Delete operations are supported for managing movie records in the database.
Data models include movie titles, descriptions, genres, release dates, and ratings.
2. Database Configuration
The application is configured with a relational database (e.g., MySQL, PostgreSQL).
Proper entity mapping and relationships (if applicable) are implemented using JPA/Hibernate.
3. File Handling (Upload & Management)
Users can upload movie-related files, such as posters or trailers, into a specific folder within the project.
These files are managed efficiently with proper validation and error handling for file size, format, etc.
4. Exception Handling
Custom exceptions are implemented to handle different error scenarios, ensuring that meaningful error messages are returned to the client.
Global exception handling is done using @ControllerAdvice for consistency.
5. Pagination & Sorting
The API supports pagination and sorting for efficiently retrieving large sets of movie records.
Clients can specify page numbers, page sizes, and sorting criteria (e.g., by title, release date, rating).
6. Spring Security with JWT Authentication
The API is secured using Spring Security with JWT (JSON Web Token) for user authentication and authorization.
Endpoints are protected, and access is restricted based on user roles (e.g., admin, user).
Token-based authentication ensures secure stateless access.
7. Forgot/Reset Password Functionality
The API supports password reset functionality.
Users can request a password reset link via email.
Tokens are generated and validated to allow secure password updates.
8. Testing APIs with Security
Comprehensive testing is done using JUnit and Spring Boot Test to ensure that all endpoints are secure and functional.
API endpoints are tested with both valid and invalid JWT tokens to validate security configurations.
