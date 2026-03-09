# Task Manager API

A simple REST API for managing tasks built with Django REST Framework.

## API Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | `/api/tasks/` | Get all tasks |
| POST | `/api/tasks/` | Create a new task |
| GET | `/api/tasks/{id}/` | Get a single task |
| PUT | `/api/tasks/{id}/` | Update a task |
| DELETE | `/api/tasks/{id}/` | Delete a task |

## Technologies Used
- Python
- Django
- Django REST Framework
- SQLite

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/dustyn-schellenberg/my-first-api.git
   cd my-first-api