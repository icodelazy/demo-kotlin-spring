# Demo Kotlin Spring Application

A simple Spring Boot application using Kotlin to demonstrate RESTful API functionality with a message resource.

## Overview

This project showcases a basic Spring Boot application written in Kotlin. It includes a RESTful API for managing messages, with endpoints for retrieving and posting messages. The application utilizes Spring Data JDBC for database interaction.

## Features

- **RESTful API:** Exposes endpoints for retrieving and posting messages.
- **Data Persistence:** Utilizes Spring Data JDBC to interact with a database.
- **Kotlin:** Written entirely in Kotlin, taking advantage of its concise and expressive syntax.
- **Spring Boot:** Built on the Spring Boot framework for easy configuration and deployment.

## Getting Started

Follow these steps to run the application locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/demo-kotlin-spring.git
   ```
2. Navigate to the project directory:

   ```bash
   cd demo-kotlin-spring
   ```
3. Run the application:
   ```bash
   ./gradlew bootRun
   ```

The application will start, and you can access the API at http://localhost:8080.

## API Endpoints

### Get Messages
```http
GET http://localhost:8080/
```
Retrieves a list of all messages.

### Post Message
```http
POST http://localhost:8080
Content-Type: application/json
{}
```
Posts a new message. The message should be sent as JSON in the request body.

Request Body Example
```json
{
  "text": "Hello, World!"
}
```

## Technologies Used
- ### Kotlin: A modern and concise programming language.
- ### Spring Boot: A powerful framework for building Java-based enterprise applications.
- ### Spring Data JDBC: A data access framework for relational databases.
- ### H2 database
