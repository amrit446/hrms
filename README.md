# HRMS Lite

## 📌 Project Overview

**HRMS Lite** is a lightweight Human Resource Management System designed to manage employees and basic HR operations efficiently.
The project is built with a modern frontend + backend architecture, focusing on simplicity, scalability, and ease of use.

It is suitable for small to medium organizations that need a basic HR system without heavy complexity.

---

## 🛠 Tech Stack Used

### Frontend

* React.js
* Axios (for API calls)
* HTML5, CSS3
* JavaScript (ES6+)

### Backend

* FastAPI (Python)
* SQLAlchemy (ORM)
* JWT Authentication
* Uvicorn (ASGI Server)

### Database

* Postgres

### Tools & Utilities

* Git & GitHub
* dotenv (Environment variable management)
* Postman (API testing)

---

## ▶️ Steps to Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/amrit446/hrms.git
cd hrms
```

---

### 2️⃣ Backend Setup

#### Create Virtual Environment

```bash
cd backend
python -m venv venv
```

#### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

#### Install Dependencies

```bash
pip install -r requirements.txt
```

#### Create `.env` File

```env
DATABASE_URL=postgresql+psycopg2://postgres:password@localhost:5432/hrms_lite
JWT_SECRET=your_secret_key
```

#### Run Backend Server

```bash
uvicorn app.main:app --reload
```

Backend will run at:

```
http://127.0.0.1:8000
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend will run at:

```
http://localhost:3000
```

---

⚠️ Assumptions & Limitations

* This is a basic HRMS, not a full-scale enterprise system.
* Role-based access control is limited.
* Payroll, attendance biometric integration, and advanced reporting are not included.
* Security features are suitable for learning/demo purposes, not for highly sensitive enterprise data.
* Email notifications and file uploads are not implemented yet.

---

📌 Future Enhancements

* Role-based access control (Admin / HR / Employee)
* Attendance & Leave Management
* Payroll module
* Email notifications
* Dashboard & analytics

---

👤 Author

**Amrit Bharti**
