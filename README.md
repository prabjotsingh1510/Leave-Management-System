Leave Management System

A full-stack Leave Management System that allows employees to apply for leave and for administrators to review, approve, or reject leave requests. This project includes both frontend and backend components along with database setup scripts and optional face-recognition utilities.

🚀 Features

✔ Apply for leave with details (type, duration, reason)
✔ Admin panel to approve/reject requests
✔ Leave balance tracking
✔ Modular backend APIs (leaveManagementAPIs)
✔ Frontend user interface (Leave-Management-FrontEnd)
✔ Database schema and seed SQL (leave_management.sql)
✔ Docker support for easy setup (docker-compose.yml)
✔ Optional face recognition utilities (save_face.py / verify_face.py)

🛠️ Technology Stack

This system is built using multiple technologies (frontend + backend):

Frontend:

JavaScript / HTML / CSS

Backend:

PHP / Node.js / Express (or similar REST APIs – adjust as per your implementation)

Database:

SQL (MySQL or compatible)

DevOps:

Docker & Docker-Compose support

📂 Project Structure
📦 Leave-Management-System
├── Leave-Management-FrontEnd/         # Frontend web app
├── leaveManagementAPIs/               # Backend APIs
├── leave_management.sql               # Database schema + seed data
├── docker-compose.yml                 # Docker config
├── web.Dockerfile                     # Dockerfile for web service
├── save_face.py                       # Optional face data script
└── verify_face.py                     # Optional face verification script

🧩 Setup & Installation
1. Clone the Repository
git clone https://github.com/prabjotsingh1510/Leave-Management-System.git
cd Leave-Management-System

2. Configure Database

Import the SQL schema:

mysql -u <username> -p < leave_management.sql


Create a database (example):

CREATE DATABASE leave_management;
USE leave_management;
SOURCE leave_management.sql;

3. Configure Backend

Provide database credentials (in your config file or environment variables):

DB_HOST=localhost
DB_USER=root
DB_PASS=your_password
DB_NAME=leave_management

4. Run with Docker (Optional)
docker-compose up --build


Your app services will start automatically.

🧑‍💻 How to Use

✔ Visit the frontend in your browser to submit leave requests.
✔ Login as an admin to manage leave applications.
✔ Use API endpoints for integration or custom UIs.
