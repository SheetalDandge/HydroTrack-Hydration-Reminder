# 💧 HydroTrack – Hydration Reminder System

A Django-based web application designed to help users maintain healthy hydration habits by tracking their water intake and supporting regular hydration reminders.

## 📌 About the Project

HydroTrack is a web-based hydration management system developed using Python and Django. The main objective is to encourage users to stay hydrated by providing a platform for managing their daily hydration activities.

The application includes user authentication and profile management, providing a foundation for personalized hydration tracking.

## ✨ Features

- **User Registration:** New users can create an account.
- **User Login:** Registered users can securely access their accounts.
- **User Profile Management:** User profiles are automatically created when a user registers.
- **Hydration Management:** Designed to support daily water intake tracking.
- **Hydration Reminders:** Focuses on encouraging users to maintain regular water-drinking habits.
- **Django Backend:** Uses Django for application logic and backend functionality.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python 3.13.5 | Backend programming |
| Django 5.2.3 | Web framework |
| SQLite | Local development database |
| HTML | Web page structure |
| CSS | Styling |
| JavaScript | Frontend interactions |

## 📂 Project Structure

```text
HydroTrack/
│
├── hydration_project/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── tracker/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── signals.py
│   └── admin.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/SheetalDandge/HydroTrack-Hydration-Reminder.git
```

### 2. Navigate to the Project Folder

```bash
cd HydroTrack-Hydration-Reminder
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows PowerShell:

```bash
venv\Scripts\Activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply Database Migrations

```bash
python manage.py migrate
```

### 7. Run Django Development Server

```bash
python manage.py runserver
```

### 8. Open in Browser

Visit:

```text
http://127.0.0.1:8000/
```

## 🎯 Project Objective

The objective of HydroTrack is to develop a simple and user-friendly hydration management application that encourages healthy water-drinking habits through technology.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Django web application development.
- Python backend programming.
- User authentication and registration.
- Django models and database management.
- Django signals and automatic profile creation.
- Managing project dependencies and virtual environments.
- Version control using Git and GitHub.

## 👩‍💻 Developer

**Sheetal Dandge**

- GitHub: [SheetalDandge](https://github.com/SheetalDandge)
- Project Repository: [HydroTrack – Hydration Reminder System](https://github.com/SheetalDandge/HydroTrack-Hydration-Reminder)

---

⭐ If you find this project interesting, feel free to explore the repository!
