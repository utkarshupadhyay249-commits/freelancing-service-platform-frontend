# Freelancing Service Platform - Frontend

A React-based frontend for a freelancing service platform that connects customers with tech experts.

## Features

- Customer and Tech Expert registration and login
- Role-based user interfaces
- Browse and view available services
- Service category management
- Tech Experts can add and manage services
- Customers can request services
- Tech Experts can respond to service requests
- Customers can approve or deny expert proposals
- Customer wallet and payment integration
- Service request status tracking
- User profile management
- Responsive web interface

## Tech Stack

### Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- Bootstrap
- Axios
- React Router
- React Toastify

### Backend

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Maven
- REST APIs

### Database & Services

- MySQL
- Razorpay

## Project Structure

```text
src/
├── CategoryComponent/
├── NavbarComponent/
├── PageComponent/
├── ServiceComponent/
├── UserComponent/
├── images/
├── App.js
├── App.css
└── index.js
```

## Backend

This frontend communicates with a Spring Boot REST API backend.

Backend repository:

https://github.com/utkarshupadhyay249-commits/freelancing-service-platform-backend

## Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/utkarshupadhyay249-commits/freelancing-service-platform-frontend.git
```

### 2. Open the project

```bash
cd freelancing-service-platform-frontend
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm start
```

The application will run at:

```text
http://localhost:3000
```

## Backend Requirement

The Spring Boot backend should also be running for API-based features to work correctly.

Backend default URL:

```text
http://localhost:8080
```

To start the backend, run:

```bash
.\mvnw spring-boot:run
```

## Application Flow

```text
Customer
   ↓
Browse Services
   ↓
Request Service
   ↓
Tech Expert Reviews Request
   ↓
Expert Sends Proposal
   ↓
Customer Approves / Denies
   ↓
Service Request Status Updated
```

## Author

Utkarsh Upadhyay
