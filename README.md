# Full Stack Todo App

A simple full-stack Todo application developed as a learning project to explore how frontend and backend technologies work together to build dynamic web applications.

The project uses **HTML, CSS, and JavaScript** for the client side, while **Node.js, Express.js, and MongoDB** power the server side and data storage.

## Tech Stack

### Frontend
- HTML5 – Application structure.
- CSS3 – Styling and layout.
- JavaScript – Client-side functionality and API communication.

### Backend
- Node.js – JavaScript runtime environment.
- Express.js – Backend web framework and API development.
- MongoDB – Database for storing todo items.

## Features

- Create new todo tasks.
- View existing tasks.
- Update todo information.
- Delete tasks.
- Store todo data in MongoDB.
- Communicate with the backend through HTTP requests.

## Project Structure

```text
TODO-APP/
│
├── client/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── server/
    ├── models/
    ├── routes/
    ├── config/
    ├── server.js
    ├── package.json
    └── .env
```

*Note: Adjust the structure above to match the actual project files.*

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the project

```bash
cd TODO-APP
```

### 3. Set up the backend

```bash
cd server
npm install
```

### 4. Configure environment variables

Create a `.env` file inside the server directory:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

### 5. Start the server

```bash
npm start
```

If you haven't configured a start script, you can run:

```bash
node server.js
```

### 6. Run the client

Open the client's `index.html` file in your browser or use the VS Code Live Server extension.

## Learning Objectives

This project provides hands-on experience with:

- Understanding client-server architecture.
- Connecting a frontend application to a backend API.
- Building RESTful API endpoints.
- Implementing CRUD (Create, Read, Update, Delete) operations.
- Working with Node.js and Express.js.
- Connecting applications to MongoDB.
- Handling HTTP requests and responses.
- Understanding how data flows between the frontend, backend, and database.

## Project Purpose

This project was created for educational purposes as part of my journey in learning full-stack web development.

The main goal is to strengthen my understanding of backend development, database integration, API communication, and how different technologies work together to build a complete web application.

## Author

**Unlisted Code Logic**

Learning, building, and documenting the journey of becoming a better developer.

---