# Question app (Django Polls)
A simple web application built with Django that allows administrators to create and manage questions and choices

## Live Demo
* App: https://question-app-wac1.onrender.com
* Admin: https://question-app-wac1.onrender.com/admin/

## Features
* Create, edit, delete questions
* Add multiple choices for each question
* Admin dashboard for content management
* Responsive web interface
* Deployed online for public access

## Installation
### 1. Clone repository

```bash
git clone https://github.com/venus-nguyen/question-app.git
cd mysite
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate # Linux/Mac
venv/Scripts/activate #Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Create superuser

```bash
python manage.py createsuperuser
```

### 6. Run server

```bash
python manage.py runserver
```

### Access
Open: http://127.0.0.1:8000/polls/
Admin: http://127.0.0.1:8000/admin/


