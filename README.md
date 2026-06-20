# Real-Time Chat Application 

A **Real-Time Chat Application** built using **Node.js**, **Express.js**, **Socket.IO**, and **React.js**, enabling instant communication between multiple users through WebSockets.

---

## Overview

The Real-Time Chat Application allows users to exchange messages instantly using WebSocket technology. It provides seamless real-time communication with a responsive frontend and a powerful backend capable of handling multiple simultaneous connections.

The application uses **Socket.IO** for bidirectional communication between the client and server, ensuring reliable and fast message delivery.

---

## Features

*  Real-time one-to-one and group messaging
*  Instant message synchronization using Socket.IO
*  Multiple users can chat simultaneously
*  Live user connection management
*  Automatic message broadcasting
*  Responsive user interface
*  Fast and reliable communication over WebSockets

---

## Technologies Used

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js
* Socket.IO

---

## Dependencies

### Frontend

* react
* react-dom
* axios
* socket.io-client

### Backend

* express
* socket.io
* cors
* dotenv
* nodemon

---

## Project Structure

```text
Real-Time-Chat-App/
│
├── client/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/
│   ├── routes/
│   ├── socket/
│   ├── server.js
│   └── package.json
│
├── README.md
└── .env
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Real-Time-Chat-App.git
cd Real-Time-Chat-App
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

### 3. Install Frontend Dependencies

```bash
cd ../client
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the **server** directory.

```env
PORT=5000
```

### 5. Start the Backend Server

```bash
cd server
npm run dev
```

### 6. Start the Frontend

```bash
cd client
npm start
```

### 7. Open the Application

Visit the application at:

```text
http://localhost:3000
```

Open multiple browser windows or devices to test real-time messaging.

---

## How It Works

1. Users connect to the chat application through the React frontend.
2. The frontend establishes a WebSocket connection with the Express server using Socket.IO.
3. When a user sends a message, it is transmitted to the server.
4. The server instantly broadcasts the message to all connected users.
5. Every connected client receives the message in real time without refreshing the page.

---

## Future Enhancements

* User authentication and login
* Private messaging
* Group chat rooms
* Online/offline user status
* Typing indicators
* Message timestamps
* File and image sharing
* Chat history storage
* Emoji support
* Push notifications

---

## Learning Outcomes

This project demonstrates:

* Real-time communication using WebSockets
* Socket.IO client-server integration
* Full-stack application development
* React component-based UI development
* Express.js backend development
* Event-driven programming
* Frontend and backend integration

