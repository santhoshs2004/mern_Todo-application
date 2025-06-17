## MERN Stack Todo List Application
This project is a simple Todo List Application developed using the MERN stack — MongoDB, Express.js, React.js, and Node.js. The backend handles API requests and database operations, while the frontend provides a clean user interface for users to manage their tasks.

## Tech Stack
## Frontend: 
React.js (Vite), 

Tailwind CSS, 

Axios, 

React Icons

## Backend: 
Node.js, 
Express.js,
MongoDB (Mongoose),
dotenv,
CORS

## Tools: 
Nodemon (for development)

## Features
Add, update, delete, and fetch todos.
Full-stack MERN architecture.
Proxy setup to handle CORS issues during development.
Tailwind CSS for styling.
Modular backend with Models, Routes, and Controllers.

## Project Setup
## 1️⃣ Backend Setup
Open VS Code and create frontend and backend folders.

Inside the backend directory, initialize Node.js project:
npm init -y

npm install express mongoose cors dotenv

npm install nodemon -D

Modify package.json:

![Screenshot 2025-06-17 211955](https://github.com/user-attachments/assets/30623a6b-8b6b-469f-a9c7-3bf9c2dc93f2)


## Create the backend folder structure:

![Screenshot 2025-06-17 212003](https://github.com/user-attachments/assets/fbd3c486-5f09-40ea-b0ea-0f67e770f118)


## Inside .env file:

MONGO_URL=<your-mongodb-url>
Connect MongoDB in config/db.js and setup routes, models, controllers as per your Todo logic.

## Start backend server:
npm run dev

##  2️⃣ Frontend Setup
In a new terminal, navigate to frontend directory:
cd frontend
Create React app using Vite:
npm create vite@latest

Choose:

Framework: React

Variant: JavaScript

Install frontend dependencies:

npm install
Install Tailwind CSS:
npm install tailwindcss @tailwindcss/vite
Modify vite.config.js to add Tailwind plugin:

![Screenshot 2025-06-17 212016](https://github.com/user-attachments/assets/61b5a99b-733c-4add-a281-810fbd985bd0)


Configure Tailwind CSS:

In src/index.css, remove existing code and paste:
@import "tailwindcss";

Install additional frontend dependencies:
npm install axios react-icons
Start frontend server:
npm run dev

## Development Flow
Build backend API endpoints in Express.

Connect MongoDB for data storage.

Build React frontend UI components.

Connect frontend with backend using Axios.

Test complete functionality.

Folder Structure Summary

![Screenshot 2025-06-17 212025](https://github.com/user-attachments/assets/f023bc92-d71d-4a09-ae01-4a251cfc656f)


Run the Full App
Start Backend (in one terminal):

npm run dev
Start Frontend (in another terminal):

npm run dev


## License
This project is licensed under the MIT License.
