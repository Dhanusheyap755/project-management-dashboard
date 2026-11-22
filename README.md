# Project Management & Task Dashboard

[![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-Build%20Tool-646CFF?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-API-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=flat&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

## 📌 Project Overview
The **Project Management Dashboard** is an agile task tracking and project workflow web application built with the **MERN stack**. Designed for software engineering teams and student project groups, it enables users to create projects, assign task items, track progress statuses, and maintain accountability across deliverables.

---

## 🎯 Problem Statement & Objectives
- **Fragmented Task Tracking:** Team members struggle to monitor status transitions across overlapping development milestones.
- **Objectives:**
  1. Build an intuitive, responsive frontend dashboard using React and Vite.
  2. Implement an asynchronous REST backend with Express.js to process task state transitions.
  3. Persist project deliverables, priorities, and deadlines with MongoDB and Mongoose.
  4. Ensure zero repository bloat with strict `.gitignore` dependency isolation.

---

## 🛠️ Technologies Used
- **Frontend:** React 18, Vite, Axios, Modern CSS
- **Backend:** Node.js, Express.js, CORS, Dotenv
- **Database:** MongoDB with Mongoose ODM
- **Linting & Code Quality:** Oxlint, ESLint

---

## 🚀 Key Features
- **Task Lifecycle Tracking:** Create, edit, update status (To Do, In Progress, Completed), and delete tasks.
- **Priority & Deadline Assignment:** Prioritize urgent deliverables with visual flags.
- **RESTful Client-Server Communication:** Clean API consumption using Axios with custom headers and error handling.
- **Modern Responsive UI:** Optimized for desktop and mobile workflows with fast Vite-powered page loads.

---

## 📂 Project Folder Structure
```
project-management-dashboard/
├── .gitignore
├── README.md
├── task-manager-backend/       # Express Backend Service
│   ├── models/                 # Mongoose schemas
│   ├── routes/                 # API endpoint routing
│   ├── package.json
│   └── server.js               # Database connection and middleware setup
└── task-manager-frontend/      # React Vite Frontend Client
    ├── src/
    │   ├── components/         # Dashboard & task card components
    │   ├── App.jsx             # Main application layout
    │   └── main.jsx
    ├── package.json
    └── vite.config.js
```

---

## 💻 Installation & Execution Instructions

### 1. Backend Setup
```bash
cd task-manager-backend
npm install
npm run dev
```

### 2. Frontend Setup
```bash
cd ../task-manager-frontend
npm install
npm run dev
```

---

## 🔮 Future Enhancements
- Interactive Drag-and-Drop Kanban board interface (dnd-kit).
- Real-time collaborative task updates via WebSockets.
- File attachment support for project specifications and design assets.
