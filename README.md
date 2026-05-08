FRONTEND README.md
# Team Task Manager Frontend

A modern and responsive frontend application for the Team Task Manager platform built using React, Vite, and Tailwind CSS. The application enables users to securely manage tasks, track progress, and collaborate efficiently through an intuitive user interface.

---

## Live Application

### Frontend Deployment
https://YOUR-VERCEL-URL.vercel.app

### Backend API
https://team-task-manager-backend-bfgy.onrender.com
---
## Overview

The frontend provides a complete task management experience with authentication, protected routes, task CRUD operations, filtering, and status management. It communicates with a RESTful backend API and supports persistent user sessions.

---

## Features

### Authentication
- User Registration
- Secure Login
- JWT-based Session Management
- Persistent Authentication using Local Storage
- Protected Routes

### Task Management
- Create Tasks
- View All Tasks
- Update Task Status
- Delete Tasks
- Task Prioritization
- Due Date Support

### User Experience
- Responsive Design
- Clean Dashboard UI
- Search and Filtering
- Real-Time Interface Updates
- Mobile-Friendly Layout

---

## Tech Stack

### Frontend Technologies
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router DOM

---

## Project Structure

```bash
frontend/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   ├── App.jsx
│   └── main.jsx
│
├── public/
├── package.json
└── vite.config.js
Installation and Setup
Clone Repository
git clone https://github.com/YOUR_USERNAME/team-task-manager-frontend.git
Navigate to Project
cd frontend
Install Dependencies
npm install
Configure Environment Variables

Create a .env file inside the frontend directory:

VITE_API_URL=https://team-task-manager-backend.o
Start Development Server
npm run dev
Deployment

The frontend application is deployed using:

Vercel
Core Functionalities
REST API Integration
React Hooks State Management
Dynamic Routing
Authentication Workflow
Environment-Based Configuration
Responsive User Interface
Future Enhancements
Dark Mode
Drag-and-Drop Task Board
Team Collaboration Features
Notifications and Reminders
Activity Tracking
Real-Time Updates
![Login Page](https://raw.githubusercontent.com/ErrabelliSathvik/team-task-manager-frontend/main/screenshots/login.png)

![Tasks Page](https://raw.githubusercontent.com/ErrabelliSathvik/team-task-manager-frontend/main/screenshots/task.png)

Author
Sathvik Errabelli

Computer Science Engineering Student
Full Stack Developer | Python Developer

GitHub:
https://github.com/ErrabelliSathvik

License

This project is intended for educational, learning, and portfolio purposes.


---

# BACKEND README.md

```md id="6kbl0x"
# Team Task Manager Backend

A scalable backend API service for the Team Task Manager platform built using Node.js, Express.js, MongoDB Atlas, and JWT Authentication. The backend handles authentication, task management, authorization, and secure database operations through RESTful APIs.

---

## Live API

https://team-task-manager-backend-bfgy.onrender.com

---

## Overview

The backend provides secure and efficient APIs for user authentication, task management, project handling, and database interactions. It follows RESTful architecture principles and integrates with MongoDB Atlas for persistent cloud-based storage.

---

## Features

### Authentication & Security
- User Registration
- Secure Login System
- JWT Authentication
- Password Hashing using bcrypt
- Protected API Routes

### Task Management APIs
- Create Tasks
- Retrieve Tasks
- Update Task Status
- Delete Tasks
- Priority and Due Date Support

### Database & Server
- MongoDB Atlas Integration
- Mongoose Schema Modeling
- Express Middleware Architecture
- Environment Variable Configuration
- Error Handling Middleware

---

## Tech Stack

### Backend Technologies
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT
- bcrypt.js
- dotenv
- cors

---

## Project Structure

```bash
backend/
│
├── config/
│   └── db.js
│
├── controllers/
│
├── middleware/
│
├── models/
│
├── routes/
│
├── server.js
└── package.json
Installation and Setup
Clone Repository
git clone https://github.com/YOUR_USERNAME/team-task-manager-backend.git
Navigate to Project
cd backend
Install Dependencies
npm install
Environment Variables

Create a .env file inside the backend directory:

VITE_API_URL=https://team-task-manager-backend.onrender.com
JWT_SECRET=sathviksecret
PORT=5000
Run Development Server
node server.js
API Endpoints
Authentication Routes
Method	Endpoint	Description
POST	/api/auth/register	Register new user
POST	/api/auth/login	Authenticate user
Task Routes
Method	Endpoint	Description
GET	/api/tasks	Retrieve all tasks
POST	/api/tasks	Create new task
PUT	/api/tasks/:id	Update task status
DELETE	/api/tasks/:id	Delete task
Project Routes
Method	Endpoint	Description
GET	/api/projects	Retrieve projects
POST	/api/projects	Create project
Deployment
Backend Hosting
Render
Database Hosting
MongoDB Atlas
Core Functionalities
RESTful API Architecture
JWT Token Authentication
Password Encryption
Middleware-Based Authorization
MongoDB Relationship Management
Secure Environment Configuration
Future Enhancements
Role-Based Access Control
API Rate Limiting
File Upload Support
Team Collaboration APIs
Notification System
WebSocket Integration
Audit Logs
Author
Sathvik Errabelli

Computer Science Engineering Student
Full Stack Developer | Python Developer

GitHub:
https://github.com/ErrabelliSathvik

License

This project is intended for educational, learning, and portfolio purposes.
