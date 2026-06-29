# FastAPI Blog

A full-stack blog application built with FastAPI, SQLAlchemy, Jinja2, and SQLite.

## Features

- Create, Read, Update, and Delete (CRUD) blog posts
- User authentication
- SQLAlchemy ORM
- SQLite database
- Jinja2 templates
- Static file support
- Form validation
- REST API endpoints

## Tech Stack

- Python
- FastAPI
- SQLAlchemy
- SQLite
- Jinja2
- HTML
- CSS

## Project Structure

```
fastapi-blog/
│
├── app/
├── templates/
├── static/
├── main.py
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/vinayakparashar01/fastapi-blog.git
```

Move into the project folder:

```bash
cd fastapi-blog
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

Windows

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
uvicorn main:app --reload
```

Open your browser:

```
http://127.0.0.1:8000
```

API Documentation:

```
http://127.0.0.1:8000/docs
```

## Future Improvements

- JWT Authentication
- Password hashing
- Image upload
- Pagination
- Search functionality
- Comments
- Likes
- Docker support
- PostgreSQL
- Deployment

## Author

**Vinayak Parashar**

GitHub: https://github.com/vinayakparashar01
