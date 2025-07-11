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
