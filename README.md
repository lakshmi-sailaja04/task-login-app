# Login Application (React + Node.js)

## Overview

This project is a simple **Login Application** built using **React (Frontend)** and **Node.js with Express (Backend)**.
It validates user credentials through a backend API and displays a welcome page on successful login.

## Features

* Login page with **username and password**
* Backend API for **credential validation**
* Successful login redirects to **Welcome page**
* Displays **error message** for invalid credentials
* **Remembers username** for subsequent logins using local storage
* Built using **React Functional Components and Hooks**

## Tech Stack

Frontend:

* React
* JavaScript
* CSS

Backend:

* Node.js
* Express.js

## Project Structure

```
login-app
│
├── frontend
│   ├── src
│   │   ├── App.jsx
│   │   ├── Login.jsx
│   │   ├── Welcome.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   └── package.json
│
└── backend
    ├── server.js
    └── package.json
```

## Installation

### 1. Clone the Repository

```
git clone <your-repository-link>
cd login-app
```

### 2. Install Backend Dependencies

```
cd backend
npm install
```

### 3. Install Frontend Dependencies

```
cd ../frontend
npm install
```

## Running the Application

### Start Backend Server

```
cd backend
node server.js
```

Server runs on:

```
http://localhost:5000
```

### Start React App

cd frontend
npm run dev


Frontend runs on:

http://localhost:5173


## API Endpoint

### POST /login

Validates user credentials.

Request Body:


{
  "username": "admin",
  "password": "admin"
}


Response:

* **200 OK** → Successful login
* **401 Unauthorized** → Invalid credentials

## Test Credentials

```
Username: admin
Password: admin
```

## Author

Developed as part of a **Full Stack Developer Technical Test**.
