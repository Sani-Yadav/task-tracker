# Task Tracker 📝

A Django-based web application for creating, updating, and managing tasks. This project provides a simple and efficient way to track work or personal tasks with an admin interface.

## 🚀 Features

- User-friendly admin panel for managing tasks
- Create, Read, Update, and Delete (CRUD) operations
- Task status tracking (e.g., Pending, In Progress, Completed)
- Simple and clean UI
- Built using Django 4+

## 🛠️ Tech Stack

- Python
- Django
- SQLite (default)
- HTML/CSS (for templates)
- Bootstrap (optional)

## 📦 Installation

Follow these steps to set up the project locally:

```bash
# Clone the repository
git clone https://github.com/Sani-Yadav/task-tracker.git
cd task-tracker

# Create virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Run the server
python manage.py runserver

task-tracker/
│
├── myapp/            # Django app for tasks
├── task-tracker/     # Project settings
├── templates/        # HTML templates
├── db.sqlite3        # Default database
└── manage.py         # Django entry point


