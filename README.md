# MERN Notes App

A simple full-stack Notes Application built using React, Node.js, Express.js, and MongoDB. The application allows users to create, view, update, and delete notes using CRUD operations.

## Features

* Create Notes
* Fetch All Notes
* Update Notes
* Delete Notes
* MongoDB Database Integration
* REST API Development
* React Frontend Integration
* Frontend Build Served from Express Backend

## Tech Stack

### Frontend

* React.js
* Axios
* CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* CORS
* Dotenv

## API Endpoints

### Create Note

POST `/api/notes`

### Get All Notes

GET `/api/notes`

### Update Note

PATCH `/api/notes/:id`

### Delete Note

DELETE `/api/notes/:id`

## Project Structure

```text
Backend/
│
├── public/           # React build files
├── src/
│   ├── config/
│   │   └── database.js
│   ├── models/
│   │   └── note.model.js
│   └── app.js
│
├── .env
├── server.js
├── package.json
└── package-lock.json

Frontend/
│
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── public/
├── package.json
└── vite.config.js
```

## How It Works

1. User creates a note from the React frontend.
2. Axios sends requests to Express APIs.
3. Express handles CRUD operations.
4. MongoDB stores and manages notes.
5. React build files are copied into Backend/public.
6. Express serves the frontend using static files.

## Installation

### Backend

```bash
npm install
node server.js
```

### Frontend

```bash
npm install
npm run dev
```

## Author

Anjali Sharma
