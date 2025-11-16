# 🍽️ Restaurant Application Backend

This repository contains the backend of my **MERN stack Restaurant Application**, built using Node.js, Express, and MongoDB. It provides secure REST APIs for menu management, orders, user authentication, and other core operations. The backend is designed with clean architecture, middlewares, and validation to ensure reliability, scalability, and smooth communication with the frontend.

---

## 🚀 Live Backend URL  
**https://restaurant-backend-production-619b.up.railway.app/**

---

## 🌐 Frontend Repo & Live URL  
**Frontend GitHub:**  
https://github.com/Vasu10134/Restaurant-Frontend  

**Frontend Live:**  
https://restrau-frontend.netlify.app/

---

## 📌 Features

- Full **CRUD** operations for restaurant resources  
- **User authentication** (Register/Login)  
- **JWT-based** secure authentication  
- **Middlewares** for auth, error handling, and request validation  
- **CORS** configured for frontend-backend communication  
- **MongoDB + Mongoose** for database modeling  
- **Validators** implemented for clean input handling  

---

## 🛠️ Tech Stack

- **Node.js**  
- **Express.js**  
- **MongoDB / Mongoose**  
- **JWT (jsonwebtoken)**  
- **CORS**  
- **Validator**

---

## 📁 Folder Structure
restaurant-backend/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
│
├── .env
├── server.js
├── package.json
└── README.md

---

## 🔧 Installation & Setup
### 1️⃣ Clone the repository

- git clone https://github.com/Vasu10134/Restaurant-Backend
- cd Restaurant-Backend

### 2️⃣ Initialize (if needed)
- npm init -y

### 3️⃣ Install required packages
- npm i cors express mongoose validator jsonwebtoken bcryptjs dotenv
---

## 🔑 Environment Variables
- Create a .env file in the root and add:
ini
- PORT=5000
- MONGO_URL=<secret>
- JWT_SECRET=<your-jwt-secret>
⚠️ Do NOT commit your .env file.
---

## ▶️ Running the Server
- npm run dev
---

## npm start
Server runs at:
http://localhost:5000
---

## 📡 API Overview (Short Summary)
- Auth Routes
- POST /api/auth/register – Create user
- POST /api/auth/login – Login & get token
- Menu / Items
- GET /api/menu – Fetch menu items
- POST /api/menu – Add item (protected)
- PUT /api/menu/:id – Update item
- DELETE /api/menu/:id – Remove item
- Orders
- GET /api/orders – Fetch orders
- POST /api/orders – Create order
(Modify based on your real routes.)
---

## 🔗 Frontend Integration
- Linked with the React frontend hosted on Netlify:
- Frontend: https://restrau-frontend.netlify.app/
- Backend: https://restaurant-backend-production-619b.up.railway.app/
- CORS settings ensure smooth communication.
---
