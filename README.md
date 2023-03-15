# JWT Authentication and Authorization

This project is a simple implementation of JWT (JSON Web Token) authentication and authorization using Spring and Spring Security.

## Features

- User registration and login using JWT authentication, with passwords encrypted using BCrypt.
- Role-based authorization using Spring Security, allowing different levels of access for different types of users.
- Customized access denied handling, ensuring that unauthorized users cannot access protected resources.
- A logout mechanism that invalidates tokens, preventing further use of the application until a new token is generated.

## Technologies

- Spring boot
- Spring Security
- Maven