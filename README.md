# 🎓 College ERP System using Django

A full-featured **College Management System** built using the **Django framework**, designed to streamline interactions between **students and teachers**. The system includes modules for **attendance tracking**, **marks management**, and **timetable scheduling**.

---

## 🚀 Features

- 🧑‍🏫 Unified login system for students and teachers  
- 📅 Timetable viewing functionality  
- 📝 Attendance management with custom date ranges  
- 📊 Marks entry and viewing  
- 🔐 Admin panel for managing:
  - Students
  - Teachers
  - Departments
  - Courses
  - Classes

---

## 🛠 Installation

Make sure you have Python and Django installed.

```bash
pip install django

▶️ Usage
Clone the repository and run the development server:
cd College-ERP
python manage.py runserver
Then open your browser and navigate to:
http://127.0.0.1:8000/
🔐 Login Credentials
The login page is shared by students and teachers.
Default Password: project123
| Role    | Username  |
| ------- | --------- |
| Student | `samarth` |
| Teacher | `trisila` |
🛡 Admin Panel
Access the Django admin panel:
http://127.0.0.1:8000/admin
Create a new admin using:
python manage.py createsuperuser
👨‍💼 Managing Users & Data
Add new students and teachers through the Admin Panel.

Modify tables like Students, Teachers, Departments, Courses, and Classes.

Attendance can be regenerated using a start and end date:

Start Date = Beginning of the attendance period

End Date = End of the attendance period

⚠️ Regenerating attendance will delete existing records for the selected period.

## Screenshot


