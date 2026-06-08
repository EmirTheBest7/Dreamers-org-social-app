# 🌐 Dreamers.org — Minimal Social Media Platform

![Django](https://img.shields.io/badge/Django-5.0-green?style=for-the-badge&logo=django)
![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql)
![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)

> A minimalistic, modern social media platform built with Django.  
Designed to demonstrate clean architecture, scalable backend design, and full-stack engineering practices.

---

## ✨ Overview

**Dreamers.org** is a lightweight social networking platform focused on simplicity, performance, and clean UX.  
It allows users to connect, share posts, and interact through a minimal but scalable social graph system.

This project was built as a **portfolio-ready full-stack application** showcasing real-world Django development skills.

---

## 🚀 Features

- 🔐 User authentication (register / login / logout)
- 👤 User profiles with avatar and bio
- 📝 Create, edit, delete posts
- ❤️ Like system for posts
- 💬 Commenting system
- 👥 Follow / unfollow users
- 📊 Personalized feed (based on following)
- 🔎 Basic user search
- ⚙️ Modular Django app structure
- 🧠 Clean architecture (service-based separation)

---

## 🧱 Tech Stack

**Backend**
- Django
- Django REST Framework
- PostgreSQL / SQLite

**Frontend**
- Django Templates
- HTML5 / CSS3
- Bootstrap 
**DevOps**
- Git & GitHub
- Environment variables (.env)
- Gunicorn (production-ready)
- Docker (optional)

---

## 📸 Screenshots

> Screenshots In Progess..!

```
In Progess..!
```

---

## 🏗️ Architecture

```
dreamers/
│
├── users/          # Authentication & profiles
├── posts/          # Post system (CRUD, likes, comments)
├── social/         # Follow system & feed logic
├── core/           # Shared utilities & base settings
├── templates/      # UI templates
└── static/         # CSS / JS / assets
```

---

## ⚙️ Installation & Setup

### 1. Clone repository
```bash
git clone https://github.com/EmirTheBest7/Dreamers-org-social-app.git
cd dreamers-org-social-app
```

### 2. Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Environment variables
Create a `.env` file:

```
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3
```

### 5. Apply migrations
```bash
python manage.py migrate
```

### 6. Create superuser
```bash
python manage.py createsuperuser
```

### 7. Run server
```bash
python manage.py runserver
```

---

## 🧪 Future Improvements

- 🔔 Real-time notifications (Django Channels / WebSockets)
- 📱 Mobile-first UI improvements
- 🧠 Recommendation feed algorithm
- 📸 Image upload optimization (S3 / Cloudinary)
- 🚀 REST API + React frontend
- 🐳 Dockerized deployment
- ☁️ Production deployment (AWS / DigitalOcean / Railway)

---

## 📈 What this project demonstrates

- Full-stack Django development
- Scalable backend architecture
- Social graph implementation (follow system)
- Clean modular project structure
- Real-world product thinking (beyond CRUD apps)

---

## 👤 Author

**Dreamers.org Project**

Emir Aliev (https://github.com/EmirTheBest7/)

---

## 📄 License

This project is licensed under the MIT License.
