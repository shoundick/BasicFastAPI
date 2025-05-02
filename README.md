# My FastAPI Project

This is a simple FastAPI application.


## 🚀 Features

- FastAPI-based web API
- Interactive Swagger docs (`/docs`)
- ReDoc documentation (`/redoc`)

## 🛠 Setup Instructions

### 1️⃣ Clone the repository

Create and activate a virtual environment
On macOS/Linux:


python3 -m venv venv
source venv/bin/activate
On Windows:

python -m venv venv
venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Run the FastAPI application

uvicorn main:app --reload

Access the app
Main app → http://127.0.0.1:8000

Swagger docs → http://127.0.0.1:8000/docs

ReDoc docs → http://127.0.0.1:8000/redoc

Requirements
Python 3.7+

FastAPI

Uvicorn