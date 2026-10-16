# Backend Fundamentals – Understanding the Backend Workflow

## 📌 Overview

This section explains the basic backend workflow and how the frontend, backend, and database communicate with each other in a web application.

I am learning backend fundamentals as part of my Agentic Full Stack Development (MERN) journey.

## 🎯 Learning Objectives

- Understand frontend and backend communication.
- Learn how client requests and server responses work.
- Understand the role of APIs.
- Learn how databases store and retrieve data.
- Understand the basic backend workflow.
- Explore Node.js and Express.js fundamentals.

## 🔄 Understanding the Backend Workflow

A typical web application follows this workflow:

1. **Frontend:** The user interacts with the application through the browser.
2. **Request:** The frontend sends an HTTP request to the backend using an API.
3. **Backend:** The server receives the request and processes the application logic.
4. **Database:** The backend retrieves or updates data in the database when needed.
5. **Response:** The backend sends the result back to the frontend.
6. **Display:** The frontend displays the response to the user.

### Workflow Diagram

```text
User
  |
  v
Frontend (React)
  |
  | HTTP Request / API Call
  v
Backend (Node.js + Express.js)
  |
  | Database Query
  v
Database (MongoDB)
  |
  | Data Response
  v
Backend Server
  |
  | HTTP Response (JSON)
  v
Frontend (React)
  |
  v
User Sees the Result
```

## 🛠️ Technologies to Learn

- HTML
- CSS
- JavaScript
- React.js
- Node.js
- Express.js
- MongoDB
- REST APIs
- JSON
- HTTP Methods

## 📚 Important Concepts

| Concept | Description |
|---|---|
| Client | Sends requests to the server |
| Server | Processes requests and returns responses |
| API | Enables communication between applications |
| Database | Stores and manages application data |
| HTTP | Protocol for client-server communication |
| JSON | Format for exchanging data |
| CRUD | Create, Read, Update, and Delete |

## 💡 Practical Example

Consider a Recipe Search App built with React.

1. The user selects a recipe category.
2. React sends an API request using Axios.
3. The backend or JSON Server receives the request.
4. Recipe data is returned in JSON format.
5. React displays the matching recipes.

Example API endpoint:

```text
GET http://localhost:4000/categories
```

This endpoint retrieves category data from a local JSON Server.

**Note:** JSON Server is useful for learning API requests and responses. It is not a replacement for building a complete backend with Node.js and Express.js.

## 🚀 My Learning Goal

My goal is to understand how frontend applications communicate with backend services and databases, and to build full-stack web applications using the MERN stack.

## 👨‍💻 Learning Journey

This README documents my learning progress in Backend Fundamentals as part of my Agentic Full Stack Development journey.

I will continue improving my practical skills by building projects and learning new backend concepts.
