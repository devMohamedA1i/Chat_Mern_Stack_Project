# Real-Time Chat Application (MERN + Socket.IO)

A full-stack real-time messaging platform built with **React**, **Chakra UI**, **Node.js**, **Express**, **MongoDB**, and **Socket.IO**, featuring JWT authentication, media uploads, and production-oriented API security middleware.

## Key Features

- **Real-Time Messaging:** Instant 1-to-1 and group chat powered by `socket.io` / `socket.io-client`.
- **Authentication & Media:** Secure registration/login with `bcryptjs` + `jsonwebtoken`, email support via `nodemailer`, and avatar/media uploads via `multer` + `cloudinary`.
- **Security Hardening:** Protected with `helmet`, `express-rate-limit`, `hpp` (HTTP Parameter Pollution protection), `joi` + `joi-password-complexity` validation, and `dompurify` sanitization.
- **Responsive UI:** Built with Chakra UI, Framer Motion, and Lottie animations.

## Tech Stack

- **Frontend:** React, Chakra UI, Framer Motion, React Router, Axios, Socket.IO Client
- **Backend:** Node.js, Express, MongoDB (Mongoose), Socket.IO, JWT, Joi, Helmet, Cloudinary

## Running Locally

```bash
# 1. Start Backend
cd backend
npm install
# Add your .env file (MONGO_URI, JWT_SECRET, CLOUDINARY_*, etc.)
npm run dev

# 2. Start Frontend (in a new terminal)
cd frontend
npm install
npm start
```

## Demo Walkthrough

![Chat Demo 1](Chat_Project1.gif)
![Chat Demo 2](Chat_Project2.gif)
![Chat Demo 3](Chat_Project3.gif)
![Chat Demo 4](Chat_Project4.gif)
