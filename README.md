# Java Spring Boot and Angular Project - Signup and Login APIs with Spring Security and JWT

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)


## Introduction

This repository contains a Java Spring Boot and Angular project that implements simple signup and login APIs with Spring Security and JWT (JSON Web Tokens). The project aims to demonstrate how to build a secure authentication system using Spring Boot for the backend and Angular for the frontend.

The backend is developed with Java Spring Boot, which provides robust security features through Spring Security, and the frontend is built with Angular, providing a user-friendly interface to interact with the signup and login APIs.

## Features

- User signup with email and password
- User login with email and password
- JWT-based authentication for secure API access
- Token-based session management

## Requirements

Before running the project, ensure you have the following prerequisites:

- Java Development Kit (JDK) 8 or higher
- Node.js and npm (Node Package Manager)
- Angular CLI (Command Line Interface)

## Setup Instructions

1. **Clone the repository:** Start by cloning this repository to your local machine using Git.

```bash
git clone https://github.com/your-username/spring-boot-angular-auth.git
cd spring-boot-angular-auth
```

2. **Backend Setup:**
   
   - Open the backend project in your preferred Java IDE (Eclipse, IntelliJ, etc.).
   - Configure your database settings in `src/main/resources/application.properties`.
   - Run the Spring Boot application to start the backend server.

3. **Frontend Setup:**

   - Navigate to the `Client FE` folder.
   - Install the required dependencies by running:

   ```bash
   npm install
   ```

   - Update the API base URL in `src/environments/environment.ts` to match your backend server URL.

4. **Running the Application:**

   - To start the Angular development server, run:

   ```bash
   ng serve
   ```

   - Visit `http://localhost:4200` in your web browser to access the application.

## Usage

1. **Signup:**

   - Open the application in your web browser and click on the "Sign Up" button.
   - Enter your email address and password, then click "Register."
   - Upon successful registration, you will be redirected to the login page.

2. **Login:**

   - On the login page, enter your registered email address and password.
   - Click on the "Login" button.
   - If the provided credentials are correct, you will be redirected to the dashboard.

3. **Dashboard:**

   - The dashboard displays a welcome message and other user-specific information.
   - The dashboard makes authenticated API requests to the backend using JWT.



## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

When contributing, please follow the existing code style, and provide detailed information about your changes or additions.


