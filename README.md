# Todo App

A full-stack Todo Application built using **React.js** for the frontend and **Django REST Framework** for the backend. This application allows users to create, view, update, and delete tasks efficiently.

## Features

* Add new tasks
* View all tasks
* Update existing tasks
* Delete tasks
* Mark tasks as completed
* RESTful API integration
* Responsive user interface
* SQLite database support

## Tech Stack

### Frontend

* React.js
* Axios
* CSS

### Backend

* Django
* Django REST Framework
* SQLite

## Project Structure

```text
todo-app/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── todo_backend/
│   ├── tasks/
│   ├── manage.py
│   └── requirements.txt
│
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/Dhanaji07/Todo_app.git
cd Todo_app
```

### Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

Backend runs at:

```text
http://127.0.0.1:8000/
```

### Frontend Setup

```bash
cd frontend

npm install

npm start
```

Frontend runs at:

```text
http://localhost:3000/
```

## API Endpoints

| Method | Endpoint         | Description    |
| ------ | ---------------- | -------------- |
| GET    | /api/tasks/      | Get all tasks  |
| GET    | /api/tasks/{id}/ | Get task by ID |
| POST   | /api/tasks/      | Create task    |
| PUT    | /api/tasks/{id}/ | Update task    |
| DELETE | /api/tasks/{id}/ | Delete task    |

## Database

* SQLite3
* Automatically created after running migrations.

## Future Enhancements

* User Authentication (JWT)
* Task Categories
* Due Dates
* Search and Filter Tasks
* Deployment on AWS/Render

## Author

**Dhanaji Bhalerao**

* GitHub: https://github.com/Dhanaji07
* LinkedIn: Dhanaji Bhalerao

## License

This project is developed for learning and educational purposes.
