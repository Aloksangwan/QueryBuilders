# querybuilders 

A Django-based web project using MySQL as the backend database.

## Setup Instructions

### 1. Create Virtual Environment

On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

### 2. Install Dependencies

```bash
pip install django
pip install mysqlclient
```

### 3. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create a Superuser

```bash
python manage.py createsuperuser
```

Follow the prompts to create an admin user.

### 6. Start the Development Server

```bash
python manage.py runserver


