# 💧 Hydration Reminder Web App

A Django-based hydration reminder application to help users maintain healthy water intake habits. Built with Celery + Redis for scheduled email notifications, and includes user authentication, streak tracking, reminders, and more.

![Django](https://img.shields.io/badge/Django-5.2-green.svg)
![Celery](https://img.shields.io/badge/Celery-5.x-orange.svg)
![Redis](https://img.shields.io/badge/Redis-7.x-red.svg)
![SQLite](https://img.shields.io/badge/SQLite-lightblue.svg)

---

## 🚀 Features

- ✅ User registration, login, and profile management
- 💧 Daily water intake tracking
- 🌤️ Dynamic hydration goals 
- 🔔 Email reminders using Celery and Redis
- 🔥 Daily streaks and hydration history

---

## 🛠️ Tech Stack

- **Backend:** Django 5.2
- **Database:** SQLite (can be upgraded to PostgreSQL/MySQL)
- **Task Queue:** Celery
- **Broker:** Redis
- **Email Provider:** SMTP (Gmail)
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap (custom styling)

---

## 📦 Installation

```bash
# Clone the repo
 git clone https://github.com/kalyaniG27/Hydration_Remainder_solution.git
 cd Hydration_Remainder_solution
      
# Setup virtual environment
python -m venv .venv
source .venv/Scripts/activate  # On Windows

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser (optional)
python manage.py createsuperuser

# Start Redis server (separately)
redis-server

# Start Celery worker
celery -A hydration_project worker --pool=solo -l info

# Start Celery beat (for periodic tasks)
celery -A hydration_project beat -l info

# Run the server
python manage.py runserver
﻿# Hydration Reminder Web App
