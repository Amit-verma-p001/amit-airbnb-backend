# Airbnb Backend API

A production-ready RESTful backend application inspired by Airbnb, built using Spring Boot. The application provides secure authentication, hotel and room management, booking workflows, inventory management, payment integration with Stripe, and role-based authorization.

---

## Features

- JWT Authentication & Authorization
- Role-Based Access Control (RBAC)
- Hotel Management
- Room Management
- Inventory Management
- Booking Management
- Stripe Payment Integration
- Strategy Design Pattern
- Global Exception Handling
- Request Validation
- DTO Mapping
- RESTful APIs

---

## Tech Stack

- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Hibernate
- Maven
- JWT
- Stripe API
- Lombok

---

## Project Structure

```
src/main/java
├── advice
├── config
├── controller
├── dto
├── entity
├── exception
├── repository
├── security
├── service
├── strategy
└── util
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/Amit-verma-p001/amit-airbnb-backend.git
```

Move to project directory

```bash
cd amit-airbnb-backend
```

Configure PostgreSQL in

```
application.properties
```

Add environment variables

```
JWT_SECRET_KEY=your_secret_key

STRIPE_SECRET_KEY=your_stripe_key

STRIPE_WEBHOOK_SECRET=your_webhook_secret
```

Run the project

```bash
./mvnw spring-boot:run
```

---

## Technologies Used

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Maven
- Stripe
- JWT

---

## Future Improvements

- Swagger/OpenAPI Documentation
- Docker Support
- Redis Cache
- Email Notifications
- Unit Testing
- AWS S3 Image Upload

---

## Author

**Amit Verma**

Backend Developer | Java | Spring Boot

GitHub: https://github.com/Amit-verma-p001
