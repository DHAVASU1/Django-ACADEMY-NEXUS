# Academic Nexus - College Management System

Academic Nexus is a web-based College Management System built using the Django framework. It helps manage various academic operations and improves interaction among students, faculty, and administrative staff.

## 🚀 Features

- Student Registration and Management
- Faculty Records
- Course and Subject Allocation
- Attendance and Timetable Management
- Exam Results and Grading
- Admin Panel for Centralized Operations

## 🛠️ Technologies Used

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite (can be changed to MySQL/PostgreSQL)

## 🔧 Setup Instructions (Step-by-Step)

### 1. Create a Virtual Environment

```bash
python -m venv venv
```

### 2. Activate the Virtual Environment

- On **Windows**:
  ```bash
  venv\Scripts\activate
  ```

- On **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### 3. Install the Required Packages

```bash
pip install -r requirements.txt
```

### 4. Apply Database Migrations

```bash
python manage.py migrate
```

### 5. Create a Superuser (Admin)

```bash
python manage.py createsuperuser
```

> Follow the prompts to set username, email, and password.

### 6. Run the Development Server

```bash
python manage.py runserver
```

### 7. Access the Application

- **Frontend**: [http://127.0.0.1:8000](http://127.0.0.1:8000)  
- **Admin Panel**: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

## 📷 Screenshots

![Admin panel](https://github.com/user-attachments/assets/9cfc6998-31b7-460f-9027-c8ef9f355de0)
![Staff Panel](https://github.com/user-attachments/assets/f9779d02-dda8-450b-8af8-f0c1aa4d18af)
![Student Panel](https://github.com/user-attachments/assets/65b9e341-08ff-47b3-86b5-4ce81e67d797)


## 📄 License

This project is for educational purposes only.

---

### 👩‍💻 Developed By

**Suvarna Dhavale**
