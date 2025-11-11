# 🎓 Project Mentor Portal

A complete **Mentor–Student Management System** built using **HTML, CSS, JavaScript, and Firebase**.  
This portal allows **Admin, Staff (Mentors), and Students** to collaborate seamlessly for project assignment, file sharing, and chat.

---

## 🚀 Features

### 👩‍💼 Admin Panel
- Add or remove mentors dynamically.
- Set total student count and assign limits per mentor.
- Automatically distribute and shuffle students among mentors.
- Generate and download finalized mentor–student assignments in Excel.
- Save all mentor and student login credentials to Firebase Firestore.

### 👨‍🏫 Mentor Dashboard
- View all assigned students.
- Open a real-time chat with each student.
- Review uploaded project files (code and documentation).
- Communicate and guide students directly.

### 👨‍🎓 Student Dashboard
- Submit **unique project title** and **description** (validated to prevent duplicates).
- Upload project code files (`.zip`, `.js`, `.py`, `.cpp`, `.java`, etc.).
- Upload PDF project documentation.
- Chat in real time with assigned mentor.

---

## 🧩 Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5 / CSS3 / JS (ES6)** | Frontend structure & interactivity |
| **Firebase Firestore** | Database for users, projects, and chat |
| **Firebase Storage** | File uploads for projects & documents |
| **Firebase Hosting** *(optional)* | Deploy the portal online |
| **XLSX.js** | Export mentor–student data to Excel |

---

## 🔐 Roles & Login

| Role | Default Credentials | Description |
|------|---------------------|-------------|
| **Admin** | `admin / admin123` | Full control over mentor and student management |
| **Mentor** | Auto-generated (`lastname123`) | Can view students, chat, and view project uploads |
| **Student** | Auto-generated | Can upload files, submit project info, and chat |

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/project-mentor-portal.git
   cd project-mentor-portal
