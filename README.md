# 📦 StockEase: E-Commerce Inventory Management System

**StockEase** is a MERN-based inventory management system designed for small and medium-sized e-commerce businesses.  
It provides real-time stock tracking, supplier management, order processing, sales analytics, and low-stock alerts.  
This project is part of my **Bachelor of Information Technology** program at **Mount Kenya University**.

---

## 🚀 Features
- 🔑 **Authentication & User Roles** → Secure login for Admin and Staff
- 📦 **Inventory Management** → Add, edit, delete, and track products in real-time
- ⚠️ **Low-Stock Alerts** → Notifications for critical stock levels
- 🛒 **Order Management** → Manage pending, completed, or canceled orders
- 🏭 **Supplier Management** → Store supplier details and link them to products
- 📊 **Sales Analytics & Reports** → Visual dashboards and downloadable reports
- 📱 **Responsive Design** → Optimized for both desktop and mobile

---

## 🛠️ Tech Stack
- **Frontend** → React.js, Redux Toolkit, Tailwind CSS  
- **Backend** → Node.js, Express.js  
- **Database** → MongoDB (Atlas or local)  
- **Other Tools** → JWT Authentication, Socket.IO, Chart.js/Recharts  

---

## 📂 Project Structure
StockEase/
├── backend/ # Node.js + Express API
│ ├── models/ # MongoDB schemas
│ ├── routes/ # API routes
│ ├── controllers/# Business logic
│ └── ...
│
├── frontend/ # React + Tailwind client app
│ ├── src/
│ ├── public/
│ └── ...
│
├── README.md # Project documentation
└── ...

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/lkwambui/StockEase.git
cd StockEase

2. Backend Setup

cd backend
npm install
cp .env.example .env   # add MongoDB URI and JWT secret
npm start

3. Frontend Setup

cd ../frontend
npm install
cp .env.example .env   # add API base URL (e.g., http://localhost:5000)
npm start

Roadmap / Progress

 Project Setup (MERN stack)

 Authentication & Role Management

 Inventory CRUD Module

 Stock Alerts & Notifications

 Supplier & Order Management

 Sales Analytics & Reports

 Testing & Debugging

 Deployment (Vercel/Render + MongoDB Atlas)