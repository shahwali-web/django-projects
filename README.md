# Django REST API - Task Manager

This is a simple Task Manager project built using **Django** and **Django REST Framework**. It allows users to perform CRUD operations (Create, Read, Update, Delete) on tasks through a RESTful API.

## Features

- ✅ List all tasks (`GET /api/tasks/`)
- ➕ Create new tasks (`POST /api/tasks/`)
- 🔄 Update existing tasks (`PUT /api/tasks/<id>/`)
- ❌ Delete tasks (`DELETE /api/tasks/<id>/`)
- 🌐 Browseable API with Django REST Framework

## Sample JSON Response

```json
[
  {
    "id": 1,
    "title": "Watch a video of Express.js",
    "completed": true
  },
  {
    "id": 2,
    "title": "Complete Django REST tutorial",
    "completed": false
  },
  {
    "id": 3,
    "title": "Write README for GitHub project",
    "completed": true
  }
]
```

## Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/shahwali-web/django-projects.git
   cd django-projects
   ```

2. **Create a virtual environment**  
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**  
   ```bash
   python manage.py migrate
   ```

5. **Start the development server**  
   ```bash
   python manage.py runserver
   ```

6. **Visit the API**  
   Open your browser and go to: [http://127.0.0.1:8000/api/tasks/](http://127.0.0.1:8000/api/tasks/)

## Tech Stack

- Python
- Django
- Django REST Framework

## License

This project is licensed under the MIT License.

---

Feel free to fork the repo, improve it, or contribute!
