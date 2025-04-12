# 📝 To-Do List App (Django + React)

A simple full-stack To-Do List application built with Django REST Framework (backend) and React (frontend). This project allows users to create, update, delete, and filter tasks. It also features dark mode and deployment via Render (backend) and GitHub Pages (frontend).

## 📌 Live Demo

Frontend: [https://muripagss.github.io/todo-djangoReact/](https://muripagss.github.io/todo-djangoReact/)  

Backend (Render): [https://todo-djangobe.onrender.com/api/tasks/](https://todo-djangobe.onrender.com/api/tasks/)

## 📁 GitHub Repository

> GitHub link containing the full project files:  
👉 [https://github.com/Muripagss/todo-djangoReact](https://github.com/Muripagss/todo-djangoReact)

---

## 🚀 Backend API Endpoints (Django REST Framework)

| Method | Endpoint                      | Description                     |
|--------|-------------------------------|---------------------------------|
| GET    | `/api/tasks/`                 | Get all tasks                   |
| POST   | `/api/tasks/`                 | Create a new task               |
| GET    | `/api/tasks/<id>/`            | Get a single task by ID         |
| PATCH  | `/api/tasks/<id>/`            | Update a task (title/completed) |
| DELETE | `/api/tasks/<id>/`            | Delete a task                   |

> Base URL: `https://todo-djangobe.onrender.com/api/tasks/`

---

## ⚙️ Local Setup

### 1. Backend (Django)

```bash
cd backend
pip install -r requirements.txt
python manage.py runserver
