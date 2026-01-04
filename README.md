# Django Weblog

A **practice project** built with Django to demonstrate backend fundamentals and project structure.  
Designed for **portfolio/review purposes**, not a production system.

## Tech Stack
- Python
- Django
- PostgreSQL(configure DB in weblog/settings.py)
- HTML/CSS

## Features
- User authentication
- Blog posts management
- Media handling
- Clean app separation

## Setup
```bash
git clone https://github.com/Sakayaaa/django-weblog.git
cd django-weblog
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py loaddata fixture_final.json
python manage.py runserver
