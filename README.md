
# Flask CRUD API with Docker

A full-stack Product Management application built using Flask, PostgreSQL, SQLAlchemy, Docker, and HTML/CSS/JavaScript.

This project demonstrates CRUD operations (Create, Read, Update, Delete) through a REST API and an interactive frontend dashboard.

## Features

- Create new products
- View all products
- View a product by ID
- Update product details
- Delete products
- REST API development using Flask
- PostgreSQL database integration
- Docker containerization
- Interactive frontend dashboard

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy
- PostgreSQL
- Docker
- HTML
- CSS
- JavaScript
- Postman
- Git and GitHub

## Project Structure

```text
flask-crud-api/
│
├── app.py
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── README.md
│
└── static/
    └── index.html
```

## API Endpoints

### Product APIs

| Method | Endpoint | Description |
|---|---|---|
| POST | `/products` | Create a product |
| GET | `/products` | Get all products |
| GET | `/products/<id>` | Get a product by ID |
| PUT | `/products/<id>` | Update a product |
| DELETE | `/products/<id>` | Delete a product |

### Sample Request

```json
{
    "name": "Laptop",
    "price": 50000
}
```

## How to Run the Project

### 1. Start the PostgreSQL database

```bash
docker compose up -d flask_db
```

### 2. Start the Flask application

```bash
docker compose up --build flask_app
```

### 3. Open the Frontend

Visit the following URL in your browser:

```text
http://localhost:4000/static/index.html
```

## Application Screenshots

Screenshots of the frontend dashboard can be added here.

## Learning Outcomes

- Developed REST APIs using Flask
- Implemented CRUD operations
- Connected Flask with PostgreSQL
- Used SQLAlchemy for database operations
- Containerized the application using Docker
- Built an interactive frontend dashboard
- Managed the project using Git and GitHub

## Author

Sandhya Pidishetty

B.Tech Computer Science and Engineering (AI & ML)