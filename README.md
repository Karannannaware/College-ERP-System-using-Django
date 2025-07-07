![st3](https://github.com/user-attachments/assets/bfdd068e-704d-460b-8626-d79d732836ba)![st2](https://github.com/user-attachments/assets/db130141-f254-46aa-906c-694642fd464a)![studentpage1](https://github.com/user-attachments/assets/20631bfd-e9e6-4030-9580-13cd21e9dead)![st2](https://github.com/user-attachments/assets/c9d99467-c299-4602-9853-07764e049d52)![studentpage1](https://github.com/user-attachments/assets/a49f96bd-007a-4317-9606-6713f914245f)![t2](https://github.com/user-attachments/assets/b1047c39-d866-4cf1-8418-1fe055d1470c)# 🎓 College ERP System using Django

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
## ScreenShot:
## Teacher Page.
![Teachers pages](https://github.com/user-attachments/assets/8fceb61e-9aab-4c2c-bc10-8c54cf283ddf)
![t2](https://github.com/user-attachments/assets/e2fc00b6-903f-4123-bccd-c5e0e504a20f)
![t3](https://github.com/user-attachments/assets/663ae8c0-0ad8-4a2a-b82e-39332a67cf09)
![t4](https://github.com/user-attachments/assets/e69b66d1-5160-4b27-9358-37cf308bde50)
![t5](https://github.com/user-attachments/assets/969a1fa9-aadb-4a64-8f26-268c9ff21a3a)

## Students page.
![studentpage1](https://github.com/user-attachments/assets/fbaacc6b-2982-437b-91bd-5f452526663e)
![st2](https://github.com/user-attachments/assets/d93e47af-0182-431e-8da8-5509a7649dbf)
![st3](https://github.com/user-attachments/assets/69d5d18f-5b84-43d3-b168-b931171d4a50)


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

-----------------------------------------------------------------------------------

