# Student Management System — Spring Boot Assignment

## Requirements
- JDK 17 or newer
- Maven (or use the Maven wrapper if your IDE provides one)
- VS Code with Java extensions, or another Java IDE

## Run in VS Code
1. Extract this ZIP.
2. Open the extracted `student-management-system` folder in VS Code.
3. Confirm Java 17+ is selected.
4. Open `src/main/java/com/example/SpringBootWebApplication.java`.
5. Run the `main` method, or open the terminal in this folder and run:
   - Windows: `mvnw.cmd spring-boot:run` (if a Maven wrapper is present)
   - Otherwise: `mvn spring-boot:run`
6. Visit `http://localhost:8080/`.

## Pages
- `/` — Home
- `/about.html` — Project Creator
- `/product.html` — Product
- `/features.html` — Features
- `/contact.html` — Contact

## Before submitting
Edit `about.html` and `contact.html` to replace the sample name, course/year, email and phone with your real details. Update college/location if needed.

This assignment intentionally uses static HTML and CSS with Spring Web only. There is no Thymeleaf, database, JPA, or working CRUD backend, because those are not required by the assignment brief.
