<div align="center">

# 🚀 TaskFlow API

### Production-Ready Task Management REST API built with FastAPI

A modern full-stack task management application demonstrating clean REST API design, complete CRUD operations, SQLAlchemy ORM, and interactive API documentation. The project follows a modular architecture with a FastAPI backend and a lightweight Vanilla JavaScript frontend.

<p>

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge"/>

<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite"/>

</p>

<p>

<img src="https://img.shields.io/badge/Status-Active-success?style=flat-square"/>

<img src="https://img.shields.io/badge/API-REST-blue?style=flat-square"/>

<img src="https://img.shields.io/badge/License-MIT-success?style=flat-square"/>

</p>

</div>

---

# 📖 Overview

TaskFlow API is a task management application built to demonstrate modern backend development using FastAPI. It provides a complete RESTful API with full CRUD functionality, request validation, database integration, and interactive API documentation. The frontend communicates with the backend through the Fetch API, creating a responsive and lightweight user experience.

---

# ✨ Features

### 📋 Task Management

- Create Tasks
- View All Tasks
- Update Tasks
- Delete Tasks
- Partial Status Updates

### ⚡ REST API

- GET
- POST
- PUT
- PATCH
- DELETE

### 🛡 Backend

- FastAPI Framework
- SQLAlchemy ORM
- Pydantic Validation
- Dependency Injection
- Automatic API Documentation

### 💻 Frontend

- Responsive Interface
- Vanilla JavaScript
- Fetch API
- Dynamic DOM Updates

---

---

# 📸 Application Screenshots

The following screenshots demonstrate the Task Manager interface and the REST API documentation.

<table align="center">

<tr>
<td align="center">
<b>📝 Task Manager Dashboard</b><br><br>
<img src="https://github.com/user-attachments/assets/97815155-69c2-4cd8-ab0a-de07a2e9bed2" width="450"/>
</td>

<td align="center">
<b>📚 Swagger API Documentation</b><br><br>
<img src="https://github.com/user-attachments/assets/31d81aa8-cd27-4f45-b607-7b8b18cd7981" width="450"/>
</td>
</tr>

<tr>
<td align="center" colspan="2">
<b>🔗 API Endpoints & Testing</b><br><br>
<img src="https://github.com/user-attachments/assets/a98bf239-499c-4f5b-b93b-2394595340dd" width="900"/>
</td>
</tr>

</table>

---

# 🏗 Architecture

```text
Browser
    │
    ▼
HTML + CSS + JavaScript
    │
    ▼
FastAPI
    │
    ▼
SQLAlchemy ORM
    │
    ▼
SQLite Database
```

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Backend | FastAPI, Python |
| ORM | SQLAlchemy |
| Validation | Pydantic |
| Database | SQLite |
| Frontend | HTML, CSS, JavaScript |
| Server | Uvicorn |

---

# 📁 Project Structure

```text
TaskFlow-API/
│
├── app/
│   ├── routers/
│   ├── crud.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   └── main.py
│
├── static/
├── templates/
├── requirements.txt
└── README.md
```

---

# 🚀 Quick Start

```bash
git clone <repository-url>

cd TaskFlow-API

python -m venv venv

pip install -r requirements.txt

uvicorn app.main:app --reload
```

Open:

```
http://localhost:8000
```

Swagger:

```
http://localhost:8000/docs
```

ReDoc:

```
http://localhost:8000/redoc
```

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /tasks | Create Task |
| GET | /tasks | Get All Tasks |
| GET | /tasks/{id} | Get Task |
| PUT | /tasks/{id} | Update Task |
| PATCH | /tasks/{id} | Update Status |
| DELETE | /tasks/{id} | Delete Task |

---

# 🚀 Future Improvements

- JWT Authentication
- User Accounts
- PostgreSQL Support
- Docker Deployment
- Pagination
- Search & Filtering
- Task Categories
- Due Dates

---

# 🤝 Contributing

Contributions, feature requests, and bug reports are welcome. Feel free to open an issue or submit a pull request.

---

# 📄 License

Licensed under the MIT License.

---

<div align="center">

Built with ❤️ using FastAPI & Python

</div>
