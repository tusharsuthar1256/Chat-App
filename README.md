# 💬 Real-Time Chat App (MERN + Socket.IO)

A **real-time chat application** built with the **MERN stack** (MongoDB, Express, React, Node.js) and **Socket.IO**.  
This project was mainly created to **learn and explore Socket.IO** for real-time communication.

---

## 🚀 Features
- 🔐 User Authentication (JWT + Cookies)
- 👥 Real-time messaging with **Socket.IO**
- 💬 One-to-one chat
- 📡 Online/offline user status
- 🎨 Responsive UI (React + Tailwind CSS)

---

## 🛠️ Tech Stack
**Frontend:** React.js (Vite), Context API/Store, Axios, Tailwind CSS  
**Backend:** Node.js, Express.js, MongoDB, Socket.IO  
**Database:** MongoDB Atlas 
**Authentication:** JWT + Cookies  

---

## 📂 Project Structure

```bash
CHAT APP/
│── backend/
│   ├── node_modules/
│   ├── src/
│   │   ├── controllers/   # Controller logic
│   │   ├── lib/           # Helper functions
│   │   ├── middleware/    # Middlewares (e.g. protectRoute)
│   │   ├── models/        # Mongoose models
│   │   ├── routes/        # API routes
│   │   ├── seeds/         # DB seeding (optional)
│   │   └── index.js       # Server entry point
│   ├── .env               # Environment variables
│   ├── package.json
│   └── package-lock.json
│
│── frontend/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── constants/     # App constants
│   │   ├── lib/           # Utility functions
│   │   ├── pages/         # Pages (Login, Chat, etc.)
│   │   ├── store/         # State management
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── .env               # Frontend environment vars
│   ├── index.html
│   ├── package.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── vite.config.js
│   └── eslint.config.js
│
│── README.md
