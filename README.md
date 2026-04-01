# 📘 Journal API — Semester Project

A full-stack API system for managing a digital academic journal, built as part of a Software Engineering course at New York University.

This project implements a scalable backend service that supports CRUD operations across interconnected data models including people, manuscripts, and text, with full API documentation, testing, and deployment.

---

## 🚀 Features

- 📄 **Manuscript Management**  
  Create, update, delete, and retrieve journal submissions  

- 👤 **People Management**  
  Handle authors, editors, and contributors  

- 📝 **Text Handling**  
  Store and manage manuscript content  

- 🔗 **Relational Data Modeling**  
  Link people to manuscripts and associated text  

- 📡 **RESTful API**  
  12+ endpoints following REST principles  

- 📚 **Swagger Documentation**  
  Fully documented API using Swagger UI  

- 🧪 **Unit Testing**  
  Comprehensive test coverage using pytest  

- ⚙️ **CI/CD Pipeline**  
  Automated testing and deployment with GitHub Actions  

- ☁️ **Cloud Deployment**  
  Hosted on Heroku  

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+  
- **Backend:** Flask, Flask-RESTx  
- **Database:** MongoDB  
- **Testing:** pytest  
- **Linting:** flake8  
- **CI/CD:** GitHub Actions  
- **Deployment:** Heroku  
- **Build Tool:** Make  
- **Frontend (optional):** React  

---

## 🧩 API Overview

The API is structured around three core resources:

- People  
- Manuscripts  
- Text  

Each resource supports full CRUD operations:

```http
GET     /resource
GET     /resource/{id}
POST    /resource
PUT     /resource/{id}
DELETE  /resource/{id}
```

Additional endpoints support relationships between entities (e.g., assigning authors to manuscripts).

---

## 📖 API Documentation

Interactive API documentation is available at:

```
/swagger
```

Includes:
- Endpoint descriptions  
- Request/response schemas  
- Example payloads  

---

## 🧪 Testing

All endpoints and core logic are tested using pytest.

Run tests with:

```bash
pytest
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd journal-api
```

### 2. Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Set environment variables
```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```

### 5. Run the server
```bash
flask run
```

---

## 🏗️ Project Structure

```bash
journal-api/
│── app/
│   ├── routes/
│   ├── models/
│   ├── services/
│   └── __init__.py
│
│── tests/
│── requirements.txt
│── Makefile
│── .github/workflows/
│── app.py
```

---

## 🔄 CI/CD Pipeline

GitHub Actions automatically:
- Runs tests on every push  
- Lints code using flake8  
- Deploys to Heroku (on main branch)  

---

## 📌 Project Management

Development followed an agile workflow using a Kanban board on GitHub, including:
- Task tracking  
- Feature planning  
- Iterative development  

---

## 🎯 Learning Outcomes

- Designed and implemented a RESTful API from scratch  
- Worked with NoSQL databases (MongoDB)  
- Built and documented scalable endpoints  
- Practiced test-driven development with pytest  
- Implemented CI/CD pipelines  
- Deployed a production-ready application  

---

## 🤝 Contributors

Developed as part of a semester-long Software Engineering course at NYU.

---

## 📬 Future Improvements

- Add authentication and authorization  
- Expand frontend interface (React)  
- Improve query performance and indexing  
- Add search and filtering capabilities  

---

## ⭐ Acknowledgements

Developed for NYU Software Engineering coursework, following best practices in API design, testing, and deployment.
