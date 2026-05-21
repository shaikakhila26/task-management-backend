# Task Management API - Backend

A scalable REST API built using Node.js, Express.js, MongoDB Atlas, and JWT Authentication.

## Features

- User Registration & Login
- JWT Authentication
- Role-Based Access Control (RBAC)
- CRUD APIs for Tasks
- MongoDB Atlas Integration
- Protected Routes
- Password Hashing with bcryptjs
- API Versioning using `/api/v1`
- Error Handling
- MVC Architecture

---

# Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- bcryptjs
- Postman

---

# Folder Structure

backend/
├── controllers/
├── middleware/
├── models/
├── routes/
├── app.js
├── server.js
├── package.json
└── .env

---


## Install Dependencies

cd backend
npm install

## Create .env File

PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=supersecret

---

# Run Backend

npm run dev

Server runs on:

http://localhost:5000

---

# API Endpoints

## Authentication

### Register User

POST /api/v1/auth/register

### Login User

POST /api/v1/auth/login

---

## Tasks

### Get All Tasks

GET /api/v1/tasks

### Create Task

POST /api/v1/tasks

### Update Task

PUT /api/v1/tasks/:id

### Delete Task

DELETE /api/v1/tasks/:id

---

# Authentication

Protected routes require JWT token.

Example:

Authorization: Bearer YOUR_TOKEN

---

# Postman Collection

Postman collection is included in the repository.

---

# Scalability Considerations

- Modular MVC architecture
- JWT stateless authentication
- MongoDB indexing support
- Easily extensible modules
- API versioning implemented
- Redis caching can be added
- Docker deployment ready
- Suitable for microservice migration

---

# Future Improvements

- Refresh Tokens
- Rate Limiting
- Docker Deployment
- CI/CD Pipeline
- Unit Testing with Jest
- Redis Caching

---

# Deployment

## Backend Deployment

Render

## Database

MongoDB Atlas

---

# Author

Shaik Akhila