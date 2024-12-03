# Booking Application

This is a Booking Application project built using **Java**, **Spring Boot**, and **Hibernate** for the backend, with **React** for the frontend. The application is designed to handle booking functionalities for various use cases, offering a seamless user experience and an intuitive interface.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Installation and Setup](#installation-and-setup)
5. [API Endpoints](#api-endpoints)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

---

## Project Overview

The Booking Application allows users to:

- Manage bookings for various services.
- Register and log in securely.
- View, create, update, and cancel bookings.
- Manage user profiles and roles (e.g., admin, user).
- Support for responsive design to ensure usability across devices.

---

## Technologies Used

### Backend
- **Java** (Java 11+)
- **Spring Boot** (Spring MVC, Spring Security, Spring Data JPA)
- **Hibernate/JPA** for ORM
- **MySQL** for database management
- **Maven** for dependency management
- **JUnit** for testing

### Frontend
- **React** (JavaScript, JSX)
- **Bootstrap** for styling
- **Axios** for API calls

### Others
- **Docker** for containerization
- **GitHub Actions** for CI/CD
- **Swagger** for API documentation

---

## Features

1. **User Management**
    - User registration and login (with password encryption).
    - Role-based access control (e.g., user vs admin).

2. **Booking Management**
    - Create, read, update, and delete (CRUD) operations for bookings.
    - Calendar view for easy scheduling.

3. **Admin Panel**
    - Manage users, roles, and bookings.

4. **Responsive Design**
    - Optimized for desktops, tablets, and mobile devices.

5. **Secure API**
    - Authentication and authorization using JWT tokens.

---

## Installation and Setup

### Prerequisites
- **Java JDK** (11+)
- **Node.js** (16+)
- **Docker** (for containerization)
- **MySQL** (locally or Dockerized)

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/KamilR29/BookingAplication.git
   cd BookingAplication/backend
