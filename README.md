🚀 BOOKWORM.COM — E-Book Management System

Full-Stack E-Book Store & Rental Platform
Built with Spring Boot, React.js, MySQL, Docker & JWT

📌 Project Overview

BOOKWORM.COM is a full-stack web application designed to manage an online bookstore with e-book purchase and rental capabilities.

The system provides secure authentication, digital content management, automated royalty tracking, and a scalable REST API architecture.

This project demonstrates real-world implementation of authentication, role-based access control, database design, containerization, and full-stack integration.

🎯 Key Features
🔐 Secure Authentication

JWT-based authentication

Role-based access (Admin / User)

Secure REST API endpoints

Spring Security integration

📚 E-Book Management

Add, update, delete books (Admin)

Book categorization

Rental and purchase options

Time-based access control for rented books

🛒 Purchase & Rental System

E-book purchase functionality

Rental system with expiration tracking

Personal digital library for users

Transaction history management

💰 Royalty Management System

Automated royalty calculation

Track author earnings

Revenue tracking system

Transaction-based royalty distribution

📦 Containerized Deployment

Dockerized backend & database

Easy environment setup

Production-ready configuration

🛠️ Tech Stack
🎨 Frontend

React.js

JavaScript

HTML5

CSS3

Axios

React Router

⚙️ Backend

Java 17

Spring Boot 3

Spring Security

JWT Authentication

REST APIs

JPA (Hibernate)

Maven 3

🗄️ Database

MySQL 8

Entity Relationship Schema Design

Transaction & Royalty Tracking

🧩 Additional Technologies

.NET Core 8.0 (Secondary Module)

Entity Framework

Docker

RESTful Architecture

🏗️ System Architecture

The application follows a layered architecture:

Controller Layer
        ↓
Service Layer
        ↓
Repository Layer (JPA)
        ↓
MySQL Database

Benefits:

Clean separation of concerns

Scalable API structure

Secure authentication flow

Maintainable and testable code

📁 Project Structure
BOOKWORM.COM/
│
├── BOOKWORM_PRO/          # Spring Boot Backend
├── BookWormNET/           # .NET Core Backend Module
├── frontend-updated_29morning/  # React Frontend
│
└── README.md

🔄 Application Flow

User registers / logs in (JWT authentication)

User browses available e-books

User purchases or rents book

System records transaction

Royalty automatically calculated

Book added to user’s digital library

Rental access expires automatically (if rented)

⚙️ How to Run Locally
✅ 1. Clone Repository
git clone https://github.com/Adarsh11Sharma/BOOKWORM.COM.git
cd BOOKWORM.COM

✅ 2. Setup MySQL Database

Create a database in MySQL

Update application.properties with credentials

✅ 3. Run Spring Boot Backend
cd BOOKWORM_PRO
mvn spring-boot:run


Runs on:

http://localhost:8080

✅ 4. Run React Frontend
cd frontend-updated_29morning
npm install
npm run dev


Runs on:

http://localhost:5173

✅ 5. (Optional) Run with Docker
docker-compose up --build

🔐 Security Highlights

JWT token-based authentication

Secure password encryption

Role-based access control

Protected REST endpoints

Axios interceptor for token management

🚀 Future Enhancements

Payment gateway integration

Advanced analytics dashboard

Cloud deployment (AWS / Azure)

Microservices architecture

Recommendation system

Email notification system

👨‍💻 Author

Adarsh Sharma
Full Stack Developer

GitHub:
https://github.com/Adarsh11Sharma
Contact no:
8421505681

⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub.
