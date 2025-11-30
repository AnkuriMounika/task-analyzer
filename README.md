Task Analyzer – React + Django Full Stack App

Task Analyzer is a simple full-stack application built using:

React (Frontend)

Django REST Framework (Backend API)

It allows users to create, view, and manage tasks through a clean and simple interface.

🚀 Features

View list of tasks from Django API

Create new tasks

Automatic API fetching

Clean React UI

Fully REST-based backend

📦 Tech Stack
Frontend

React

Axios

CSS

Backend

Django

Django REST Framework

🛠️ Setup Instructions
Backend (Django)
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


API will run at:

http://127.0.0.1:8000/api/tasks/

Frontend (React)
cd frontend
npm install
npm start


React app runs at:

http://localhost:3000

🔌 API Endpoint
Method	Endpoint	Description
GET	/api/tasks/	Get all tasks
POST	/api/tasks/	Create a new task
