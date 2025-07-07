 College ERP System using Django
A full-featured College Management System built using the Django framework, designed to streamline interactions between students and teachers. The system provides essential academic functionalities like attendance tracking, marks management, and timetable scheduling.

🚀 Features
🧑‍🏫 Unified login for students and teachers

📅 Timetable viewing

📝 Attendance management (with date range)

🧾 Marks tracking system

🛠 Admin portal for managing:

Students

Teachers

Departments

Courses

Classes

🛠 Installation
Ensure Python and Django are installed:

bash
Copy
Edit
pip install django
▶️ Usage
Navigate to the project folder and start the server:

bash
Copy
Edit
cd College-ERP
python manage.py runserver
Now open your browser and go to:
🔗 http://127.0.0.1:8000/

🔐 Login Credentials
Login Page is common for both students and teachers.

Default Password: project123

Role	Username
Student	samarth
Teacher	trisila

🛡 Django Admin Panel
Access:
🔗 http://127.0.0.1:8000/admin

Default Admin:

Username: admin

Password: project123 (or your custom password)

To create a new admin:

bash
Copy
Edit
python manage.py createsuperuser
👨‍💼 Managing Users & Data
Add new students and teachers via the Admin Panel.

Modify tables like Students, Teachers, Courses, Departments, and Classes.

Use the Attendance Date Range feature to regenerate attendance entries:

Start Date = Beginning of attendance period

End Date = End of attendance period

⚠️ This will delete previous attendance data and generate new records for the selected range.

📌 Project Type
Full Stack | Web App | Django | College ERP System
