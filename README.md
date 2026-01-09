# simple-FastAPI

A simple FastAPI project created to understand the basics of backend development using Python and FastAPI.  
This project is mainly for learning, experimenting, and building confidence with APIs.

---

## 🚀 About the Project

This repository contains a minimal FastAPI application with basic routes.  
I did this project for...

- Learning FastAPI
- Exploring how APIs work
- Practicing backend concepts
- Preparing small demo or college projects

The focus is on clarity and simplicity, not complexity.

---

## 🧰 Tech Stack

- Python
- FastAPI
- Uvicorn

---

## 📦 Prerequisites

Make sure you have the following installed:

- Python 3.8 or above
- pip (Python package manager)

---

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/HarshZazadiya/simple-FastAPI.git
cd simple-FastAPI
```

🔧 Setup & Installation
1. Clone the repository
```bash
git clone https://github.com/HarshZazadiya/simple-FastAPI.git
cd simple-FastAPI
```

----
## Create a virtual environment (recommended)
```bash
python -m venv venv
```



### Activate it(virtual environment):
just type...

Windows
```bash
venv\Scripts\activate
```

Linux / macOS
```bash
source venv/bin/activate
```

---
## Install required packages

make sure to be in TodoApp directory before running this command...
If requirements.txt exists:
```bash
pip install -r requirements.txt
```

If not, install manually:
```bash
pip install fastapi uvicorn
```

(Optional) create requirements.txt:
```bash
pip freeze > requirements.txt
```
---
### ▶️ Run the Application

Start the FastAPI server:

Make sure you are in FastAPI directory and run this command to have app tun on your local host
if you are insite TodoApp just type given command to back out to FastAPI directory.
```bash
cd ..
```
```bash
uvicorn TodoApp.main:app --reload
```
---
Server will be available at:

http://127.0.0.1:8000

📄 API Documentation

FastAPI automatically generates interactive docs:

Swagger UI:

http://127.0.0.1:8000/docs


ReDoc:

http://127.0.0.1:8000/redoc


You can test all endpoints directly from the browser.
