# FSD Class - Django Application

A Full-Stack Web Development project built with **Django**, handling custom views, template rendering, and static file management.

## Features
* **Members App:** View list of members and detailed views using SQLite models.
* **Static Assets:** Global CSS configuration and static file collection (`collectstatic`).
* **URL Routing:** Custom sub-app path routing.

## Prerequisites
* Python 3.13+
* Django 6.1+

## Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/FSD_class.git
   cd FSD_class
   ```

2. **Create and activate virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On macOS/Linux
   ```

3. **Install Django:**
   ```bash
   pip install django
   ```

4. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

6. Open your browser and navigate to `http://127.0.0.1:8000/testing/`.
