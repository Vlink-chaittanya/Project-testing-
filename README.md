# Sample API Project

A production-ready REST API built using Python and FastAPI.

## Features

- RESTful API
- JWT Authentication
- CRUD Operations
- Docker Support
- API Documentation
- Logging
- Unit Testing
- Environment Configuration

---

## Tech Stack

- Python 3.12
- FastAPI
- PostgreSQL
- SQLAlchemy
- Docker
- Pytest

---

## Project Structure

```
src/
tests/
docs/
```

---

## Installation

Clone the repository.

```bash
git clone https://github.com/example/sample-api-project.git
```

Navigate to the project.

```bash
cd sample-api-project
```

Create a virtual environment.

```bash
python -m venv venv
```

Activate it.

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

Install dependencies.

```bash
pip install -r requirements.txt
```

---

## Running the Project

```bash
uvicorn src.app:app --reload
```

Application runs on

```
http://localhost:8000
```

Swagger Documentation

```
http://localhost:8000/docs
```

ReDoc

```
http://localhost:8000/redoc
```

---

## Running Tests

```bash
pytest
```

---

## Docker

Build

```bash
docker build -t sample-api .
```

Run

```bash
docker-compose up
```

---

## Environment Variables

Copy

```
.env.example
```

to

```
.env
```

and update the values.

---

## API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /users | Get all users |
| GET | /users/{id} | Get user |
| POST | /users | Create user |
| PUT | /users/{id} | Update user |
| DELETE | /users/{id} | Delete user |

---

## Documentation

See the **docs** folder for detailed documentation.

- Architecture
- Deployment
- API Reference

---

## Contributing

Please read CONTRIBUTING.md before submitting a pull request.

---

## License

MIT License
