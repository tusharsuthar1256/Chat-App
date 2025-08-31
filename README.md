


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
````

---

## ⚡ Installation & Setup

### 1️⃣ Clone the repo

```bash
git clone https://github.com/your-username/chat-app.git
cd chat-app
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
npm start
```

Create a `.env` file inside `backend/`:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
PORT=5000
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Create a `.env` file inside `frontend/`:

```env
VITE_BACKEND_URL=http://localhost:5000
```

---

## 📸 Screenshots

(Add your app screenshots here)

* Login Page
* Chat Dashboard
* Real-time Messaging

---

## 🎯 Learning Purpose

This project was mainly created to **practice and understand Socket.IO** with the **MERN stack** and see how real-time communication works in web applications.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📬 Contact

👤 **Tushar Suthar**

* GitHub: [tusharsuthar1256](https://github.com/tusharsuthar1256)
* LinkedIn: [Tushar Suthar](https://in.linkedin.com/in/tushar-suthar-469163260)
* X (Twitter): [@TusharS08423915](https://twitter.com/TusharS08423915)

```

---

Would you like me to also add a **Demo GIF/Preview section** at the top (so visitors see the app in action immediately)?
```
