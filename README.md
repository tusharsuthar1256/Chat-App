


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
NODE_ENV=development
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
PORT=5000
CLOUDINARY_CLOUD_NAME=cloud_name
CLOUDINARY_API_KEY=api_key
CLOUDINARY_API_SECRET=secret_key
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```


---

## 📸 Screenshots

(Add your app screenshots here)

* Login Page
<img width="1733" height="835" alt="image" src="https://github.com/user-attachments/assets/05aa5cc0-2edf-4f37-bc16-e91bf37d4f82" />

*Signup Page
<img width="1733" height="835" alt="image" src="https://github.com/user-attachments/assets/5346161d-6375-4012-84b9-fb6bae6d8fd8" />

* Chat Dashboard
<img width="1733" height="835" alt="image" src="https://github.com/user-attachments/assets/8453dd09-ad72-4d4a-897e-0454d6241039" />

* Profile Page
<img width="1733" height="1012" alt="image" src="https://github.com/user-attachments/assets/3bc54b0a-b843-441c-8ad1-66fcc670fe75" />

* Theme Changer
<img width="1733" height="1066" alt="image" src="https://github.com/user-attachments/assets/1426085c-5554-436a-9f9b-4e4ee321b969" />


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

