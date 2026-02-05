
# Leave Management System

A full‑stack **Leave Management System** that allows employees to apply for leave and administrators to review, approve, or reject leave requests. This project includes both frontend and backend components along with database setup scripts and optional face‑recognition utilities.

---

## 🚀 Features

- Apply for leave with details (type, duration, reason)  
- Admin panel to approve or reject requests  
- Leave balance tracking  
- Modular backend APIs  
- Frontend user interface  
- Database schema and seed SQL  
- Docker support for easy setup  
- Optional face recognition utilities  

---

## 🛠️ Technology Stack

**Frontend:**  
- HTML, CSS, JavaScript  

**Backend:**  
- PHP / Node.js / REST APIs  

**Database:**  
- MySQL  

**DevOps:**  
- Docker, Docker Compose  

---

## 📂 Project Structure

```
Leave‑Management‑System
├── Leave‑Management‑FrontEnd/
├── leaveManagementAPIs/
├── leave_management.sql
├── docker‑compose.yml
├── web.Dockerfile
├── save_face.py
└── verify_face.py
```

---

## 🧩 Setup & Installation

### 1. Clone the Repository

```
git clone https://github.com/prabjotsingh1510/Leave-Management-System.git
cd Leave-Management-System
```

### 2. Database Setup

```
CREATE DATABASE leave_management;
USE leave_management;
SOURCE leave_management.sql;
```

### 3. Run with Docker (Optional)

```
docker-compose up --build
```

---

## 🧑‍💻 Usage

- Open frontend in browser  
- Submit leave request  
- Login as admin to manage requests  

---

## 🤝 Contributing

Fork the repo, create a branch, make changes, and submit a pull request.

---

## 📄 License

Open Source Project.
