# 📝 Quick Tasks App

A simple, dark-themed full-stack task manager built with **React**, **Tailwind CSS**, **Express.js**, and **MongoDB**. Easily add, toggle, and delete tasks with real-time backend syncing.

---

## 🚀 Features

- ✅ Add tasks (with duplicate check and input trimming)
- 🔁 Toggle task completion
- ❌ Delete tasks
- 🌑 Dark mode UI using Tailwind CSS
- ⚡ Live updates without page refresh
- 🧠 Clean, maintainable code with full CRUD
- 📦 Backend powered by MongoDB + Mongoose

---


## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS, Axios
- **Backend**: Express.js, MongoDB, Mongoose
- **API**: RESTful endpoints (`/api/tasks`)

---

## 📦 Installation Guide

### 1. Clone the repository
```
git clone https://github.com/Mabella29/SimpleTask.git
cd SimpleTask

```
---

### 2. Install dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd ../server
npm install
```

---

### 3. Configure environment variables

Create a `.env` file inside the `server` folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

> Replace `your_mongodb_connection_string` with your actual MongoDB URI.

---

## ▶️ Running the App

### Start the backend

```bash
cd server
npm start
```

This should show `MongoDB connected successfully` in the terminal.

### Start the frontend

```bash
cd ../frontend
npm run dev
```

Now open your browser and visit:

```
http://localhost:5173
```

---

## 📂 Project Structure

```
quick-tasks/
├── client/
│   ├── components/
│   ├── services/
│   ├── App.jsx
│   ├── Home.jsx
├── server/
│   ├── config/
│   ├── controller/
│   ├── model/
│   ├── routes/
│   └── server.js
```

