# 🎬 BookMyShow Clone (Django)

A full-stack Django project that replicates core features of a movie booking platform like BookMyShow. It supports user login, movie listing, theater seat booking, and also exposes a RESTful API for integration.

---

## 🚀 Live Demo

🌐 [Visit the Live App](https://bookmyshow-django.onrender.com/)  

---

## 🛠 Features

- 🧑 User registration & login
- 🎞️ Movie listing and filtering
- 🎟️ Theater & seat booking system
- ✅ Booking confirmation
- 🔌 REST API for movies (`/movies/api/movies/`)
- 🔐 Protected seat booking (login required)

---

## 🧰 Tech Stack

| Layer     | Tech Used                              |
|-----------|----------------------------------------|
| Backend   | Python, Django, Django REST Framework  |
| Frontend  | Django Templates (HTML, CSS)           |
| Database  | SQLite                                 |
| Deployment| Render (Free Tier)                     |
| Version Control | Git & GitHub                     |

---

## 📦 Installation (Local)

```bash
git clone https://github.com/your-username/bookmyshow-django.git
cd bookmyshow-django
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
