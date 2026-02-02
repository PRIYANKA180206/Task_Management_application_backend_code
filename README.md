# Task Management Backend

A simple **Task Management Backend** built using **FastAPI** and **PostgreSQL**.  
It supports full CRUD operations for tasks with proper validation and professional Git workflow.

---

## **Features**
- Create, Read, Update, Delete tasks
- PostgreSQL database integration
- Data validation using Pydantic
- RESTful API endpoints
- Professional Git workflow with feature branches and Pull Requests

---

## **Tech Stack**
- **Backend:** FastAPI
- **Database:** PostgreSQL
- **Version Control:** Git & GitHub

---

## **Installation**

1. Clone the repository:
```bash
git clone [https://github.com/PRIYANKA180206/Task_Management_application_backend_code.git]
cd Task_Management_application_backend_code

2.Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3.Install dependencies:
pip install -r requirements.txt

4.Setup PostgreSQL database:
Create a database (e.g., task_management_db)
Update config.py or .env with database credentials

5.Run the FastAPI server:
uvicorn main:app --reload

Tip:-Test APIs using Postman or Swagger UI:
http://127.0.0.1:8000/docs

