# 💬 Feedback System

A full-stack feedback collection application built with **React** (frontend) and **Node.js + Express** (backend), using **MongoDB** for data storage. This project is scaffolded with Vite for fast development and includes ESLint for code quality.

---

## 📌 Features

- Submit and view feedback entries
- RESTful API with Express.js
- MongoDB integration via Mongoose
- React frontend with Vite and HMR
- ESLint for code linting

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, JavaScript, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Linting**: ESLint

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local instance or Atlas)

### Installation

1. **Clone the repository:**

   bash - git clone https://github.com/Abimathi03/feedback_system.git
   bash - cd feedback_system

3. **Install backend dependencies:**

   bash - cd server
   bash - npm install

4. **Configure environment variables:**

   env - MONGO_URI=your_mongodb_connection_string
PORT=5000

5. **Start the backend server:**

   bash - npm run dev

6. **Install frontend dependencies:**

   bash - cd ../client
   bash - npm install

6.**Start the frontend development server:**

   bash - npm run dev

## 📄 API Endpoints

Base URL: http://localhost:5000/api/feedback

- GET / – Retrieve all feedback entries
- POST / – Submit new feedback
- GET /:id – Retrieve feedback by ID
- DELETE /:id – Delete feedback by ID
