# MERN Chat App

![MERN Chat App](https://img.shields.io/badge/MERN-Stack-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange)

A real-time chat application built using the MERN stack (MongoDB, Express.js, React, and Node.js). This app allows users to create accounts, join chat rooms, and communicate in real-time.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)

## Features

- Real-time messaging using Socket.io
- User authentication (JWT)
- Create and join chat rooms
- Private messaging
- Responsive UI design
- Emoji support
- Chat history stored in MongoDB
- Typing indicators

## Technologies

- **Frontend**:

  - React
  - Redux (or Context API for state management)
  - Material-UI (or Bootstrap for styling)
  - Socket.io-client

- **Backend**:

  - Node.js
  - Express.js
  - MongoDB (Mongoose for ODM)
  - Socket.io
  - JWT for authentication

- **Other**:
  - WebSocket for real-time communication
  - bcrypt.js for password hashing
  - dotenv for environment variables
  - nodemon for development

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/mern-chat-app.git
   cd mern-chat-app
   ```

2. **Install dependencies**:

- **Backend**:

  ```
  cd backend
  npm install
  ```

- **Frontend**
  ```
  cd frontend
  npm install
  ```

3. **Environment Variables**
   Create a .env file in the backend directory and add the following variables:

   ```
   PORT=
   MONGO_DB_URL=

   JWT_SECRET =

   NODE_ENV =
   ```

4. **Debugging**

- **Backend**

  ```
  cd backend
  npm run server
  ```

- **Frontend**

  ```
  cd frontend
  npm start
  ```
