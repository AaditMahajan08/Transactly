# 💰 Expense Tracker App

A full-stack Expense Tracker application built with:

- 📦 **Backend**: Node.js, Express, MongoDB
- 🖥️ **Frontend**: React.js (Vite)

---

## 🚀 Getting Started

### 📁 Folder Structure

```
project-root/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/            <-- Create this folder manually
│   ├── .env                <-- Create this manually
│   ├── package.json
│   └── server.js
│
└── frontend/
    └── expense-tracker/
        ├── public/
        ├── src/
        ├── package.json
        └── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

#### 📄 Create a `.env` file in the `backend/` folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

#### 📂 Create the `uploads/` folder

```bash
mkdir uploads
```

#### ▶️ Run the backend server

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend/expense-tracker
npm install
```

#### ▶️ Run the frontend app

```bash
npm run dev
```

---

## 📝 Notes

- Make sure MongoDB is running locally or use a cloud database (like MongoDB Atlas).
- The backend runs on `http://localhost:5000` by default.
- The frontend (Vite) usually runs on `http://localhost:5173`.

---

## 📂 Environment Variables Reference (`.env.example`)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---


## 📄 License

This project is licensed under the MIT License.
