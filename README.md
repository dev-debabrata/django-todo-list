# ✅ Django To-Do List App

A simple and elegant To-Do List web application built with **Django**, **HTML**, and **CSS**. Users can create, update, mark as complete, and delete tasks.

---

## 📌 Features

- 📝 Add new tasks
- ✅ Mark tasks as complete/incomplete
- 🗑️ Delete tasks
- 🧠 Clean UI with HTML/CSS
- 🔐 Optional: User login/logout (if enabled)

---

## 🚀 Technologies Used

- Python 3.x
- Django 4.x
- HTML5 & CSS3
- SQLite (default Django DB)

---

## 🛠️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/django-todo-list.git
cd django-todo-list
python -m venv venv
pip install -r requirements.txt
pip install django
python manage.py migrate
python manage.py runserver
---
django-todo-list/
│
├── todo/           
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   │   └── todo/
│   │       ├── index.html
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── todo_project/        
│   ├── settings.py
│   ├── urls.py
│
├── db.sqlite3          
├── manage.py
└── requirements.txt
```
