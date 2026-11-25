Student Management System

Project Overview

This project is a Student Management System developed using Python and Django as part of the Django Internship Program.

The main purpose of this project is to manage student-related information, departments, courses, and student enrollments in an organized way.

Technologies Used

- Python
- Django 5.2
- SQLite3
- Visual Studio Code
- Git and GitHub

Installation and Setup

1. Clone the repository

git clone https://github.com/athit10/sms-django-internship.git
cd sms-django-internship

2. Create a virtual environment

py -m venv venv

3. Activate the virtual environment

venv\Scripts\Activate.ps1

4. Install dependencies

pip install -r requirements.txt

5. Apply database migrations

python manage.py migrate

6. Run the development server

python manage.py runserver

Open the following URL in your browser:

"http://127.0.0.1:8000/"

Project Structure

sms_project/
│
├── config/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md

Explanation of Files

- manage.py: Used to execute Django commands such as running the server and applying migrations.
- settings.py: Contains the main project settings, including database configuration and installed applications.
- urls.py: Defines the main URL routes of the project.
- asgi.py: Helps run the project using asynchronous server interfaces.
- wsgi.py: Provides the entry point for synchronous web servers.
- requirements.txt: Contains the list of installed Python packages required by the project.
- .gitignore: Prevents unnecessary and sensitive files from being uploaded to GitHub.
- README.md: Provides information about the project and instructions for setting it up.

Project Progress

- [x] Django project initialized.
- [x] Virtual environment created.
- [x] Django 5.2 installed.
- [x] Database migrations applied.
- [x] Development server tested.
- [x] requirements.txt created.
- [x] .gitignore configured.
- [ ] Django applications created.
- [ ] Database models implemented.
- [ ] Django Admin configured.
- [ ] Initial data entered.

Author

Django Internship Program - Week 1