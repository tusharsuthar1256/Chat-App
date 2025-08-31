# 💬 Real-Time Chat App (MERN + Socket.IO)

This is a **real-time chat application** built using the **MERN stack (MongoDB, Express, React, Node.js)** and **Socket.IO**.  
The main goal of this project was to **learn and explore Socket.IO** for real-time communication.

---

## 🚀 Features
- 🔐 User Authentication (JWT + Cookies)
- 👥 Real-time messaging with **Socket.IO**
- 💬 One-to-one chat
- 📡 Online/offline user status
- 📷 Media/file(only images) sharing support
- 🎨 Responsive UI (React + Tailwind/Custom CSS)

---

## 🛠️ Tech Stack
**Frontend:** React.js, Context API / Redux, Axios, Tailwind CSS  
**Backend:** Node.js, Express.js, MongoDB, Socket.IO  
**Database:** MongoDB Atlas
**Authentication:** JWT + Cookies  

---

## 📂 Project Structure
```bash
chat-app/
│── backend/         # Express + Socket.IO server
│   ├── src/
│   │   ├── models/  # Mongoose models
│   │   ├── routes/  # API routes
│   │   ├── index.js # Entry point
│── frontend/        # React client
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│── README.md
