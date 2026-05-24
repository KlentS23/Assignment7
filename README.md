# Luminary

A deep purple luxury gallery with gradient aesthetics

## Features
- User registration & authentication
- Public / private photo albums
- Bulk photo uploads
- Collaborator roles (viewer / contributor / admin)
- Full-text album search

## Quick Start

```bash
cd luminary
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 8002
```

Open http://localhost:8002

## Deploy (Render / Railway)
Set env vars: `SECRET_KEY`, `DATABASE_URL`, `DEBUG=False`, `ALLOWED_HOSTS`
