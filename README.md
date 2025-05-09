# Virtusa E-Pass Project

An E-Pass portal that supports government officials in generating travel passes for citizens moving from one state to another. This application was developed as a full-stack Java web application using Spring Boot and follows the MVC architecture.

## Features

- Citizen Registration and Login
- Admin Login with Dashboard
- E-Pass Application Submission
- Admin Approval/Rejection of Pass Requests
- Check E-Pass Status by ID
- Secure Authentication & Authorization
- Role-based Access (Admin vs Citizen)

## 🛠️ Tech Stack

- **Backend**: Java, Spring Boot, Spring Security
- **Frontend**: HTML templates 
- **Build Tool**: Maven
- **Template Engine**: Thymeleaf 

## 📁 Project Structure

- `src/main/java/com/example/demo` – Java source code
  - Controllers (`controller/`)
  - Models (`model/`)
  - Repositories (`repository/`)
  - Services (`services/`)
  - Configurations (`config/`)
- `src/main/resources/templates` – HTML templates
- `src/main/resources/application.properties` – Spring Boot configuration
- `pom.xml` – Maven build file

## Security

- Spring Security integrated with custom login success handler
- Role-based access to differentiate between admin and citizen actions

## How to Run

1. Clone the repository
2. Import as a Maven project in your IDE (e.g., IntelliJ or Eclipse)
3. Update `application.properties` with DB credentials (if needed)
4. Run `EPassprojectApplication.java`

