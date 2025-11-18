Uber Clone – Full Stack Ride Booking Application

A full-stack Uber-like ride booking system built using React (Vite) + Node.js + Express + MongoDB + Socket.io.
Users can create accounts, login, request rides, connect with captains, and receive real-time updates.

📌 Features
👤 User Features

User Signup with validation

User Login with JWT authentication

Protected routes using React Router

Live tracking & ride updates

Real-time ride request + acceptance (Socket.io)

Logout & token handling

🚗 Captain Features

Captain registration & login

Captain profile management

Accept ride requests in real-time

Live communication using WebSockets

⚡ System Features

JWT-based Authentication

Password hashing using bcrypt

MongoDB & Mongoose models

Real-time events (Socket.io)

Secure APIs with validation

Ride model with status tracking

🛠️ Tech Stack
Frontend

React.js (Vite)

Tailwind CSS

Axios

React Router

Context API

Socket.io-client

Backend

Node.js

Express.js

MongoDB (Mongoose)

JWT Authentication

Bcrypt

Express-validator

CORS

Cookie-parser

Socket.io

* Folder Structure 
uber-video-main/
│
├── Backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── db/
│   ├── socket/
│   ├── app.js
│   ├── server.js
│   └── .env
│
└── frontend/
    ├── src/
    │   ├── pages/
    │   ├── components/
    │   ├── context/
    │   ├── App.jsx
    │   └── main.jsx
    └── .env
