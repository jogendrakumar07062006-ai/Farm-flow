# 🌾 Farm-flo

Farm-flo is a full-stack **MERN (MongoDB, Express.js, React, Node.js)** e-commerce platform built specifically for farmers.  
It enables farmers to **buy, sell, and manage agricultural products efficiently** through a modern web interface.

The goal of Farm-flo is to **digitize local agricultural markets** and make product trading easier, faster, and more transparent.

---

## 🚀 Tech Stack

- **Frontend:** React.js, Vite, CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT (JSON Web Tokens)  
- **Email Service:** Mailtrap  
- **Version Control:** Git & GitHub  

---

## ✨ Features

### 🔐 Authentication & Security

- User registration and login  
- JWT-based secure authentication  
- Protected routes for authorized users  

### 📦 Product Management

- Farmers can **add, update, delete, and view products**  
- Inventory management system  
- Product listings with detailed information  

### 🛒 Order Management

- Buyers can place orders  
- Sellers can track and manage incoming orders  
- Real-time order status updates  

### 📊 Admin Dashboard

- Manage users  
- Manage products  
- Monitor orders across the platform  

### 📱 Responsive Design

- Mobile-friendly interface  
- Seamless experience on desktop, tablet, and smartphones  

### 📧 Email Notifications

- Automated email alerts using **Mailtrap**  
- Notifications for orders and updates  

---

## 📁 Project Structure

```
Farm-flo
│
├── frontend/               # React Frontend
│   ├── src/                # Source files
│   ├── public/             # Static assets
│   └── package.json
│
├── backend/                # Node.js Backend
│   ├── models/             # MongoDB Schemas
│   ├── routes/             # API Routes
│   ├── controllers/        # Request Handlers
│   ├── config/             # Database & App Config
│   └── package.json
│
└── README.md
```

---

## ⚙️ Prerequisites

Before running the project, make sure you have installed:

- Node.js (v16 or later)
- npm or yarn
- MongoDB (Local or MongoDB Atlas)
- Git

---

## 🛠 Installation & Setup

### 1️⃣ Fork & Clone the Repository

```bash
git clone https://github.com/jogendrakumar07062006-ai/Farm-flow.git
cd Farm-flow
```

### 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

### 3️⃣ Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### 4️⃣ Environment Variables

Create a `.env` file inside the **backend** folder:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_secret_key
MAILTRAP_TOKEN=your_mailtrap_token
CLIENT_URL=http://localhost:5173/
EMAIL_PASS=your_email_password
```

### 5️⃣ Run the Application

#### Start Backend

```bash
cd backend
nodemon
```

#### Start Frontend

```bash
cd frontend
npm run dev
```

---

## 🌱 Future Enhancements

- 💳 Payment Gateway Integration (Stripe / Razorpay)  
- 📊 Sales analytics dashboard for farmers  
- 🌍 Multi-language support  
- 📱 Mobile App (React Native)  
- 🤖 AI-based crop price prediction  

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create a feature branch  
3. Commit your changes  
4. Open a Pull Request  

---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you like this project, consider **starring the repository!**
