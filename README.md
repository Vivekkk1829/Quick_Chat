
# 💬 Real-Time Chat Application

A full-stack **Real-Time Chat Application** built using **React (Vite)**, **Node.js**, **Express**, **MongoDB**, and **Socket.IO**.  
The application supports instant messaging with real-time updates, online user presence.

---


---

## 🧾 Overview

This project demonstrates a production-ready real-time chat system using **WebSockets (Socket.IO)** along with RESTful APIs.  
It focuses on scalability, clean architecture, and real-time communication between users.

---

## 🚀 Features

- 🔐 User authentication
- 💬 One-to-one real-time messaging
- 🟢 Online / Offline user presence
- ✍️ Typing indicators
- ⚡ Real-time updates using Socket.IO
- 🌐 REST APIs for users & messages
- 🎨 Modern frontend with React + Vite
- ☁️ Deployment-ready (Vercel / Render)

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- Axios
- Context API
- Socket.IO Client

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT Authentication
- dotenv
- CORS

---

## 🧠 System Architecture

- **Frontend** handles UI, authentication state, and socket connections
- **Backend (Express)** exposes REST APIs
- **Socket.IO Server** handles real-time events
- **MongoDB** stores users and messages

---


---

## ⚙️ Environment Variables

### Backend (`server/.env`)

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### Frontend (`client/.env`)

```
VITE_BACKEND_URL=http://localhost:5000
```

---

## ▶️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/real-time-chat-application.git
cd real-time-chat-application
```

### 2️⃣ Start Backend

```
cd server
npm install
npm run dev
```

Backend runs at:
```
http://localhost:5000
```

### 3️⃣ Start Frontend

```
cd client
npm install
npm run dev
```

Frontend runs at:
```
http://localhost:5173
```



---


---



