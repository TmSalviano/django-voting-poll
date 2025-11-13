# Django Voting Poll App

A web-based voting application built with Django.

## 🚀 Features

- Create and manage polls
- Vote on polls with real-time results
- Admin interface for poll management
- Performance monitoring with Django Debug Toolbar

## 🛠️ Technologies

- Django 4.2+
- SQLite Database
- Django Debug Toolbar
- CSS

## 📦 Quick Setup

```bash
git clone https://github.com/yourusername/django-voting-app.git
cd django-voting-app

python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Visit `http://localhost:8000` to use the app.

## 📁 Project Structure

```
django-voting-app/
├── my_site/                 # Main voting app
├── polls/          # Project settings
|-- templates/
├── requirements.txt      # Dependencies
└── manage.py            # Django management
```

## 🎯 Usage

- **Create Polls**: Admin interface or web forms
- **Vote**: Simple one-click voting
- **View Results**: Real-time results
- **Debug**: Django Debug Toolbar for performance monitoring

Visit `http://localhost:8000/admin` for admin access after creating a superuser with `python manage.py createsuperuser`.
