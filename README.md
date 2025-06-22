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

## ✨ Features

### 1. User Authentication

- Users can register and log in securely using email and password.
- Signup includes an option to upload a profile image (stored in the `uploads/` folder).
- Email and password fields are validated (e.g., password must be at least 8 characters).
- Users can toggle visibility of their password input during login and signup.

### 2. Dashboard Overview

- Displays total balance, total income, and total expense at a glance.
- Lists recent transactions with associated icons and color-coded amounts.
- Shows a donut chart summarizing the financial overview for easy interpretation.

### 3. Income Page

- Lists all income entries with title, date, and amount.
- Provides an income trends bar chart over time.
- Shows breakdown by income sources (e.g., trading, interest).
- Includes a modal to add new income transactions with emoji icons and details.

### 4. Expense Page

- Displays expense items with category, date, and amount.
- Includes a bar chart showing the last 30 days of expenses.
- Donut chart summarizing income vs expense.
- Modal allows adding new expense entries with detailed inputs and emoji categories.

### 5. Add Transaction Modal

- Modal forms allow users to add both income and expenses.
- Emoji picker for category icons enhances visual clarity.
- Inputs for source, amount, date, and description.
- Real-time UI updates reflect added data instantly.

### 6. Data Visualization

- Charts and graphs display financial data trends over time.
- Visual elements include:
  - Bar chart for monthly transactions.
  - Donut charts for distribution of income and expenses.
  - Line chart for expense trends.

### 7. Responsive Design

- The entire app is responsive and adapts to different screen sizes.
- Sidebar navigation for easy access to dashboard, income, expense, and logout.
- Clean, gradient-based UI with a modern look and feel.


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
