# Student Record Management System

A simple Django-based web application and REST API to manage student records including their name, class, age, roll number, marks, and grade.

---

## Features

- Add, update, view, and delete student records via web UI
- REST API endpoints for CRUD operations on students
- Search, filter, and order students by name, class, and marks
- Pagination support for API responses

---

## Tech Stack

- Python 3.x
- Django 5.2.1
- Django REST Framework
- SQLite3 (default development database)

---

## Project Structure
studentrecord/
├── manage.py
├── studentrecord/
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
├── tasks/
│ ├── migrations/
│ ├── models.py
│ ├── views.py
│ ├── admin.py
│ ├── apps.py
│ ├── urls.py
│ ├── serializers.py
│ ├── forms.py
│ └── templates/
│ └── tasks/
│ ├── student_list.html
│ ├── student_create.html
│ ├── student_update.html
│ └── student_delete.html
└── db.sqlite3
## Screenshots

### Student List Page
![Student List](screenshots/student_list.png)

### Add New Student Page
![Add Student](screenshots/student_create.png)
