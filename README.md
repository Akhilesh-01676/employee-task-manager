# Employee Task Manager

A full-stack MERN application for managing employee tasks.

## Features

* User Registration
* User Login
* JWT Authentication
* Add Tasks
* View Tasks
* Mark Tasks as Completed
* Delete Tasks
* Logout Functionality

## Tech Stack

### Frontend

* React
* Vite
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas
* Mongoose

## Installation

### Clone Repository

```bash
git clone https://github.com/Akhilesh-01676/employee-task-manager.git
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## API Endpoints

### Authentication

* POST `/api/auth/register`
* POST `/api/auth/login`

### Tasks

* GET `/api/tasks`
* POST `/api/tasks`
* PUT `/api/tasks/:id`
* DELETE `/api/tasks/:id`

## Author

Akhilesh Yadav
