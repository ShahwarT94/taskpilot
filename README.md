# TaskPilot

**TaskPilot** is a full-stack task management application built with:

- Flask (Python) backend using PostgreSQL
- Nginx-hosted HTML/CSS/JavaScript frontend
- PostgreSQL database
- Docker Compose for orchestration

---

## Features

- Create, delete, and toggle tasks
- Task priorities (low, medium, high)
- Persistent PostgreSQL database
- Full Docker Compose support (backend, frontend, database)
- Deployed on an EC2 instance for cloud demonstration

---

## Tech Stack

| Component  | Technology                    |
|------------|-------------------------------|
| Backend    | Flask, Flask-CORS, SQLAlchemy |
| Frontend   | HTML, CSS, JavaScript         |
| Database   | PostgreSQL                    |
| DevOps     | Docker, Docker Compose        |
| Hosting    | AWS EC2                       |

---

## Quick Start (Local)

### Prerequisites

- Docker
- Docker Compose

### Run the Application

```bash
git clone https://github.com/your-username/taskpilot.git
cd taskpilot
docker-compose up --build


Once started, access the application at:

Frontend: http://localhost:8080

Backend API: http://localhost:5050/tasks

Project Structure
swift
Copy
Edit
taskpilot/
├── backend/
│   ├── app.py
│   └── requirements.txt
├── frontend/
│   └── [static HTML/CSS/JS files]
├── docker-compose.yml
API Endpoints
Method	Endpoint	Description
GET	/tasks	List all tasks
POST	/tasks	Create a new task
PUT	/tasks/<task_id>	Toggle task status
DELETE	/tasks/<task_id>	Delete a task

Author
Shahwarr Shamim
Cloud Engineering and Software Development
LinkedIn: www.linkedin.com/in/muhammad-shahwar-shamim-aa140b263

License
This project is licensed under the MIT License.

