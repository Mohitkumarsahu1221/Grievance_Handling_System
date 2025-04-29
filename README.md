# 📢 Grievance Handling System

A full-stack Django-based web application to streamline the submission, tracking, escalation, and resolution of grievances within an organization. This system supports role-based access,
real-time grievance updates, feedback collection, data visualization, and report export.

## 🚀 Features

- 📝 **Submit Grievances**
- 👥 **Role-Based Dashboards** for Admin, Employee, and Customer
- ⚙️ **Admin Panel for Department & Grievance Assignment**
- ⏱️ **Automatic Escalation** of unresolved grievances after 2 days
- ⭐ **Feedback Submission** with rating & comment after resolution
- 📊 **Dashboard Analytics** with Charts
- 📄 **Filtered Reports & CSV Export** for Admins

---

## 🔧 Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Database:** SQLite3
- **Visualization:** Chart.js
- **Version Control:** Git, GitHub
- **IDE/Tools:** Visual Studio Code

---

## ⚙️ Setup Instructions

Make sure Django 5.1 or higher and MySQL is installed. 

1. **Clone Repository**
```bash
git clone https://github.com/Mohitkumarsahu1221/Grievance_Handling_System
cd grievance-handling-system
```
2. Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```
3. Run Development Server
```bash
python manage.py runserver
```
4. Users
• You can create customers and Employees easily, and for Admins one Admin superuser is already made(username: Admin; Pass: 1234pass).
• To create more Admin users one can create manually or can go to <a href="http://127.0.0.1:8000/register-admin">Register Admin<a/> when you are logged in as admin to register New Admin.
---

## 🙌 Acknowledgements
**Django Documentation** – https://docs.djangoproject.com/

**Bootstrap** – https://getbootstrap.com/

**Chart.js** – https://www.chartjs.org/
