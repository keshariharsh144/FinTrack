![Matrix SVG](./assets/matrix.svg)
<div align="center">
  
# 💰 FinTrack

### Personal Finance & Expense Management Dashboard

**FinTrack** is a modern full-stack expense management application built with the **MERN stack**, designed to make personal finance tracking simple and organized. It allows users to manage their income and expenses, monitor their overall financial balance, analyze spending through interactive visualizations, and export transaction data to Excel. With secure authentication and a clean, responsive interface, FinTrack provides an intuitive way to keep track of everyday finances.


<br/>

![React](https://img.shields.io/badge/React-2026-blue?logo=react\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Fast-purple?logo=vite\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green?logo=node.js\&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-API-black?logo=express\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb\&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Authentication-black?logo=jsonwebtokens\&logoColor=white)

<br/>

**⭐ If you find FinTrack useful, consider giving it a star!**

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🔐 Authentication

Secure user signup and login using **JWT authentication** and **bcrypt password hashing**.

</td>
<td width="50%">

### 📊 Financial Dashboard

Get a clear overview of your **income, expenses, balance, and financial activity**.

</td>
</tr>

<tr>
<td width="50%">

### 💸 Expense Management

Add, categorize, view, and delete your expenses with ease.

</td>
<td width="50%">

### 💰 Income Management

Track your income sources and maintain a complete financial record.

</td>
</tr>

<tr>
<td width="50%">

### 📈 Interactive Analytics

Understand your financial activity through **interactive charts and visualizations**.

</td>
<td width="50%">

### 📥 Excel Export

Export your financial records to **Excel** for analysis and record keeping.

</td>
</tr>

<tr>
<td width="50%">

### 📅 Time-Based Filtering

Analyze your financial activity across different time periods.

</td>
<td width="50%">

### 📱 Responsive UI

Clean and responsive interface designed for different screen sizes.

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### Frontend

| Technology          | Usage               |
| ------------------- | ------------------- |
| ⚛️ **React.js**     | User interface      |
| ⚡ **Vite**          | Development & build |
| 🎨 **Tailwind CSS** | Styling             |
| 📊 **Recharts**     | Data visualization  |
| 📡 **Axios**        | API communication   |

### Backend

| Technology        | Usage               |
| ----------------- | ------------------- |
| 🟢 **Node.js**    | Runtime environment |
| 🚂 **Express.js** | REST API            |
| 🍃 **MongoDB**    | Database            |
| 🦫 **Mongoose**   | Database modeling   |
| 🔑 **JWT**        | Authentication      |
| 🔐 **bcrypt.js**  | Password hashing    |
| 📊 **XLSX**       | Excel export        |

---

## 🏗️ Project Structure

```text
FinTrack/
│
├── 📂 backend/
│   ├── 📂 config/
│   │   └── db.js
│   ├── 📂 controllers/
│   │   ├── dashboardController.js
│   │   ├── expenseController.js
│   │   ├── incomeController.js
│   │   └── userController.js
│   ├── 📂 middleware/
│   │   └── auth.js
│   ├── 📂 models/
│   │   ├── expenseModel.js
│   │   ├── incomeModel.js
│   │   └── userModel.js
│   ├── 📂 routes/
│   │   ├── dashboardRoute.js
│   │   ├── expenseRoute.js
│   │   ├── incomeRoute.js
│   │   └── userRoute.js
│   ├── 📂 utils/
│   │   └── dateFilter.js
│   ├── .env.example
│   ├── package.json
│   └── server.js
│
├── 📂 frontend/
│   ├── 📂 public/
│   ├── 📂 src/
│   │   ├── 📂 assets/
│   │   ├── 📂 components/
│   │   ├── 📂 pages/
│   │   ├── 📂 utils/
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── .env.example
│   ├── package.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### 📋 Prerequisites

Before running FinTrack, make sure you have:

* **Node.js & npm**
* **MongoDB Atlas** account or local MongoDB
* **Git**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/keshariharsh144/FinTrack.git
cd FinTrack
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder with your MongoDB connection string and JWT secret.

Then start the server:

```bash
npm start
```

Backend:

```text
http://localhost:4000
```

### 3️⃣ Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
```

Create a `.env` file inside the `frontend` folder:

```env
VITE_API_URL=http://localhost:4000
```

Start the development server:

```bash
npm run dev
```

Open the URL provided by Vite.

---

## 🔄 How It Works

```text
┌─────────────────────────┐
│     ⚛️ React Frontend   │
│       + Vite            │
└────────────┬────────────┘
             │
             │ REST API
             ▼
┌─────────────────────────┐
│   🟢 Node.js + Express  │
│        Backend          │
└────────────┬────────────┘
             │
             │ Mongoose
             ▼
┌─────────────────────────┐
│      🍃 MongoDB         │
│        Database         │
└─────────────────────────┘
```

FinTrack follows a **client-server architecture** where the React frontend communicates with the Express backend through REST APIs.

User authentication is handled using **JWT**, while MongoDB stores user accounts and financial transactions.

---

## 🔑 Key Highlights

* 🏛️ **MVC Architecture** for organized backend development
* 🔐 **JWT-protected APIs** for secure financial operations
* 🗄️ **MongoDB + Mongoose** for structured data management
* 🧩 **Reusable React Components** for maintainable UI
* 📊 **Interactive Data Visualization** with Recharts
* 📥 **Excel Export** for financial records
* ⚙️ **Environment-based Configuration** for local and production environments

---

<div align="center">

## 👨‍💻 Author

### Harsh Keshari

**B.Tech Computer Science & Engineering**
**KIET Group of Institutions**

Full-Stack Developer passionate about building **modern, scalable, and user-focused web applications**.

[🐙 GitHub](https://github.com/keshariharsh144)

<br/>

### ❤️ Built with passion using the MERN Stack

**Made with ❤️ by Harsh Keshari**

⭐ **Star this repository if you like FinTrack!**

</div>
