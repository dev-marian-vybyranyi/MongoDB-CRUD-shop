# MongoDB React Shop

A simple e-commerce application built with React (Frontend) and Node.js/Express/MongoDB (Backend).

## Features

- View Products
- Add/Edit/Delete Products
- Authentication (Signup/Login)
- MongoDB Atlas Integration

## Local Setup

1.  **Clone the repository**
2.  **Install dependencies** (Root folder contains both frontend and backend dependencies):
    ```bash
    npm install
    ```
3.  **Configure Environment Variables**:
    - Create a `.env` file in the root directory (or rename `.env.example` if available).
    - Add your MongoDB connection string and Backend URL:
    ```env
    MONGODB_URI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/shop?appName=Cluster0
    REACT_APP_BACKEND_URL=http://localhost:3100
    ```
4.  **Start the Backend Server**:
    ```bash
    npm run start:server
    ```
    (Runs on port 3100)
5.  **Start the Frontend Application**:
    ```bash
    npm start
    ```
    (Runs on port 3000)