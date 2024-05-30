# hogwarts-artifacts-online

## Overview

**Hogwarts Artifacts Online** is a web application built with Spring Boot that manages wizards, artifacts, and users within a fictional Hogwarts universe. This application provides a RESTful API for creating, reading, updating, and deleting records of wizards and artifacts. It includes authentication and authorization mechanisms to ensure that only authenticated users can perform specific actions while allowing anonymous users to view public details.

## Features

- **User Authentication and Authorization**: Secure login and role-based access control.
- **CRUD Operations**: Create, read, update, and delete records for wizards and artifacts.
- **Artifact Assignment**: Assign artifacts to wizards and track ownership.
- **Data Validation and Error Handling**: Ensure reliable and accurate data management.

## Technologies Used

- **Java**
- **Spring Boot**
- **Spring Security**
- **Spring Data JPA**
- **Hibernate**
- **H2 Database** (for development and testing)
- **Maven**

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/hogwarts-artifacts-online.git
   cd hogwarts-artifacts-online
   ```

2. **Build the project**:
   ```bash
   mvn clean install
   ```

3. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

4. **Access the application**:
   Open your browser and navigate to `http://localhost:8080`.

## API Endpoints

### Wizards

- **GET /api/wizards**: Retrieve a list of all wizards.
- **GET /api/wizards/{id}**: Retrieve details of a specific wizard by ID.
- **POST /api/wizards**: Create a new wizard.
- **PUT /api/wizards/{id}**: Update an existing wizard.
- **DELETE /api/wizards/{id}**: Delete a wizard.

### Artifacts

- **GET /api/artifacts**: Retrieve a list of all artifacts.
- **GET /api/artifacts/{id}**: Retrieve details of a specific artifact by ID.
- **POST /api/artifacts**: Create a new artifact.
- **PUT /api/artifacts/{id}**: Update an existing artifact.
- **DELETE /api/artifacts/{id}**: Delete an artifact.

### User Management

- **POST /api/auth/register**: Register a new user.
- **POST /api/auth/login**: Authenticate a user and obtain a token.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

