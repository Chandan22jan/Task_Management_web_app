# MERN Task Management

A MERN application for basic tasks management system .

- 

## Installation and Setup

1. Install all the dependencies

   ```sh
   npm install
   ```



2. Start the backend

   ```sh
   npm run dev
   ```
3. Start the frontend

   ```sh
   npm start
   ```
4. Go to http://localhost:3000

## Backend API

<pre>
- POST     /api/auth/signup
- POST     /api/auth/login
- GET      /api/tasks
- GET      /api/tasks/:taskId
- POST     /api/tasks
- PUT      /api/tasks/:taskId
- DELETE   /api/tasks/:taskId
- GET      /api/profile
</pre>

## Frontend pages

<pre>
- /                 Home Screen (Public home page for guests and private dashboard (tasks) for logged-in users)
- /signup           Signup page
- /login            Login page
- /tasks/add        Add new task
- /tasks/:taskId    Edit a task
</pre>

