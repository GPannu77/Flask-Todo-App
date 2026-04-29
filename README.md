# ✅ Flask Todo App

A full-stack web application for managing tasks. Built with Python, Flask, and SQLite.

---

## 📋 Overview

This app lets you add, complete, and delete tasks through a web interface running in your browser. It uses Flask as the backend web framework and SQLite as the database to store tasks permanently.

---

## 📁 Project Structure

```
flask-todo/
│
├── app.py                  # Main Flask application
├── models.py               # Database models
│
├── templates/
│   ├── base.html           # Base template
│   └── index.html          # Main page
│
├── static/
│   └── style.css           # Styling
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/GPannu77/flask-todo.git
cd flask-todo
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the app**
```bash
python app.py
```

**4. Open in your browser**
```
http://localhost:5000
```

---

## ✨ Features

- Add new tasks
- Mark tasks as complete
- Delete tasks
- Tasks saved to a database — nothing lost on restart
- Clean responsive UI

---

## 🧱 How It's Built

| File | Responsibility |
|---|---|
| app.py | Flask routes and app logic |
| models.py | SQLite database model for tasks |
| templates/index.html | Main page UI |
| static/style.css | Page styling |

---

## 📊 Example

```
==== My Todo List ====

[ ] Buy groceries
[ ] Finish Flask project       
[x] Set up GitHub repo   ✓ Done

+ Add new task: ___________  [Add]
```

---

## 🛠️ Technologies Used

- **Python 3**
- **Flask** — web framework
- **Flask-SQLAlchemy** — database ORM
- **SQLite** — lightweight database
- **HTML/CSS** — frontend

---

## 👤 Author

Gurnoor Pannu — [GitHub](https://github.com/GPannu77)