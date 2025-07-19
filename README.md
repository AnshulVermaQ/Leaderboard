# 🏆 Leaderboard App

A full-stack Leaderboard web application where users can be added, random user points can be claimed, and claim history is tracked and displayed. Built using **React** for the frontend and **Node.js/Express** for the backend, deployed on **Render**.

---

## 🚀 Live Demo

- **Frontend**: [https://leaderboard-frontend-m4vn.onrender.com](https://leaderboard-frontend-m4vn.onrender.com)  
- **Backend**: [https://leaderboard-backend-pc2b.onrender.com](https://leaderboard-backend-pc2b.onrender.com)

---

## 🧩 Features

- ➕ Add new users to the leaderboard
- 🎯 Claim points for a **random** user
- 📜 View claim **history** for all users
- 📊 Real-time leaderboard display
- 🔒 Backend API with proper CORS configuration

---

## 🛠 Tech Stack

### Frontend
- React
- Axios
- CSS/Styled Components

### Backend
- Node.js
- Express.js
- MongoDB (or your selected DB)
- CORS middleware

---

## 🧑‍💻 Getting Started

### 📦 Clone the Repository

git clone https://github.com/AnshulVermaQ/Leaderboard.git
cd Leaderboard

🔧 Setup Backend
cd backend
npm install

Create a .env file in the backend/ folder:
PORT=5000
MONGO_URI=your_mongodb_connection_string

Start the backend:
node index.js

💻 Setup Frontend

cd ../frontend
npm install
npm run dev
