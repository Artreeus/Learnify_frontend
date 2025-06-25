# 🎓 Learnify

A full-stack **Learning Management System (LMS)** built using **TypeScript**, **Next.js**, **Express.js**, and **MongoDB**. The application includes two main interfaces:

- 👨‍💼 **Admin Dashboard**: For course and lecture management.
- 👨‍🎓 **User Panel**: For course browsing, lecture consumption, and progress tracking.

---

## 🚀 Live Demo

🔗 [Frontend (Vercel)](https://your-frontend-url.vercel.app)  
🔗 [Backend (Vercel)](https://your-backend-url.onrender.com)

### 🧪 Test Credentials

**Admin**

- Email: `admin@example.com`
- Password: `admin123`

**User**

- Email: `user@example.com`
- Password: `user123`

---

## 🛠️ Tech Stack

### Frontend

- **Next.js** with **TypeScript**
- **Tailwind CSS** for responsive UI
- **Axios** for API communication

### Backend

- **Express.js** (MVC architecture)
- **TypeScript**
- **Mongoose** (MongoDB ODM)

### Database

- **MongoDB Atlas**

---

## 📚 Features

### 🔐 Authentication

- Secure login for Admin and Users
- Role-based route protection

---

### 🛠️ Admin Dashboard

> For course creators and instructors

#### Course Management

- Upload courses with:
  - Thumbnail (image)
  - Title
  - Price
  - Description
- Edit/Delete courses
- Dynamic routing to course module management page

#### Module & Lecture Management

- Add/Edit/Delete modules and lectures
- Lecture fields:
  - Title
  - YouTube video link
  - Multiple PDF notes
- Lecture list view with filters by Course and Module

---

### 🎓 User Panel

> For learners/students

#### Course Details Page

- Displays course info dynamically
- Static sections for:
  - Reviews
  - Instructor info

#### Lecture Page

- Expandable modules with lectures
- Search bar to filter lectures by title
- Unlock lectures sequentially (next button unlocks next)
- Embedded YouTube video player
- Download/view multiple PDFs per lecture
- Visual progress indicators (progress bar/checkmarks)

---

## 🧱 Project Structure

### Frontend (`/client`)
```

/components
/pages
/styles
/utils

```

### Backend (`/server`)
```

/controllers
/models
/routes
/services
/config

```

---

## 📦 Installation

### 1. Clone the Repo

```Bash
git clone https://github.com/your-username/learnify.git
cd learnify
```

### 2. Backend Setup

```bash
cd server
npm install
cp .env.example .env  # Set up environment variables
npm run dev
```

### 3. Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

## 🧪 Environment Variables

### Backend `.env`

```ini
PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret
```

---

## 📝 Notes

- Course videos use YouTube embed links (no video hosting required).
- PDFs are stored using file upload (local or cloud storage).
- Fully responsive across desktop, tablet, and mobile.
- Modular, clean codebase following best practices and separation of concerns.

---

## ✅ Requirements Checklist

- [x] Responsive UI with Tailwind
- [x] MVC backend with Express
- [x] Dynamic content synced from backend
- [x] Admin & User separation
- [x] Lecture progress tracking
- [x] CRUD operations for courses, modules, lectures

---

## 📄 License

MIT License © 2025


