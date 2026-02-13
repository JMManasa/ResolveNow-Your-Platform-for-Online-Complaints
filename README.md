# 📌 Complaint Registry System

A Full-Stack Complaint Management System built using React, Node.js,
Express, and MongoDB.

------------------------------------------------------------------------

## 🚀 Features

### 👤 User

-   Sign Up / Login
-   Register Complaint
-   View Complaint Status
-   Chat with Assigned Agent

### 🧑‍💼 Agent

-   View Assigned Complaints
-   Update Complaint Status
-   Chat with User

### 🛠 Admin

-   View All Users
-   View Agents
-   Assign Complaints to Agents
-   Delete Users

------------------------------------------------------------------------

## 🛠 Tech Stack

### Frontend

-   React.js
-   React Router
-   Axios
-   Bootstrap / MDB React UI

### Backend

-   Node.js
-   Express.js
-   MongoDB
-   Mongoose
-   CORS
-   Express Session

------------------------------------------------------------------------

## 📂 Project Structure

complaint-registry/ │ ├── frontend/ │ ├── package.json │ ├── backend/ │
├── index.js │ ├── config.js │ ├── Schema.js │ ├── package.json

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Install MongoDB

Make sure MongoDB is installed and running locally.

Connection String: mongodb://127.0.0.1:27017/details

------------------------------------------------------------------------

### 2️⃣ Backend Setup

cd backend npm install npm start

Backend runs on: http://localhost:8000

------------------------------------------------------------------------

### 3️⃣ Frontend Setup

cd frontend npm install npm start

Frontend runs on: http://localhost:3000

------------------------------------------------------------------------

## 🔗 API Endpoints

### User

-   POST /SignUp
-   POST /Login

### Messages

-   POST /messages
-   GET /messages/:complaintId

### Admin

-   GET /AgentUsers
-   GET /OrdinaryUsers
-   DELETE /OrdinaryUsers/:id

------------------------------------------------------------------------

## 🧪 How to Test

1.  Start Backend
2.  Start Frontend
3.  Register as Ordinary User
4.  Register as Agent
5.  Assign complaint using Admin
6.  Test chat feature

------------------------------------------------------------------------

## 📌 Future Improvements

-   Password hashing with bcrypt
-   JWT Authentication
-   Role-based authorization
-   Deployment support


