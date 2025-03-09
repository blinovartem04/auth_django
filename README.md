# Authentication Service
Simple authentication system built with Django, allowing users to register, log in, and manage their accounts.

# Key Features
* User registration
* Login for registered users
* Basic route protection using Django authentication

# Installation and Setup
## 1. Clone the repository:
git clone https://github.com/blinovartem04/auth_django.git
cd auth_django

## 2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # For Linux/MacOS
venv\Scripts\activate     # For Windows
## 3. Install dependencies:
pip install -r requirements.txt

## 4. Apply migrations:
python manage.py migrate

## 5. Run the development server:
python manage.py runserver

## The project will be available at: http://127.0.0.1:8000.

