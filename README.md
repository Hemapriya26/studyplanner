# AI Study Planner

AI Study Planner is a full-stack web application developed using Flask that helps students create structured study schedules, manage tasks, and track learning progress efficiently. The application provides a clean and responsive interface with secure user authentication and interactive study planning features.

## Features

- User registration and login authentication
- Personalized study plan creation
- Automatic timetable generation based on subjects and study hours
- Task progress tracking
- Dashboard with study statistics
- Saved study plans management
- Responsive and modern user interface
- SQLite support for local development
- PostgreSQL support for production deployment

## Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Jinja2 Templates

### Backend
- Python
- Flask
- Flask-Login
- Flask-Bcrypt
- Flask-SQLAlchemy

### Database
- SQLite
- PostgreSQL

## Project Structure

```bash
studyplanner/
│
├── main.py
├── models.py
├── requirements.txt
├── Procfile
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── planner.html
│   └── view_plan.html
│
├── static/
│   ├── style.css
│   └── script.js
│
└── studyplanner.db
```
## Installation and Setup
## Clone the Repository
git clone https://github.com/Hemapriya26/studyplanner.git

cd studyplanner

## Create a Virtual Environment

## Windows:

python -m venv venv

venv\Scripts\activate

## macOS/Linux:

python3 -m venv venv

source venv/bin/activate

## Install Dependencies

pip install -r requirements.txt

Running the Application

python main.py

## Open the application in the browser:

http://127.0.0.1:5000

## Configure the following environment variables before deployment:

SECRET_KEY=your_secret_key

DATABASE_URL=your_database_url

## Deployment

The application can be deployed on platforms such as:

Render

Vercel

Netlify

Supabase(Database)

Recommended Start Command

gunicorn main:app

## Future Enhancements

AI-powered study recommendations

Calendar integration

Notifications and reminders

Analytics dashboard

Pomodoro timer integration

## Author:

Hemapriya P

BE.CSE

Saveetha Engineering College
