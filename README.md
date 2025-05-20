# Building a Simple Book REST API with Python 3


# Setup instructions

## 1. Setup a Virtual Environment in Python

Follow the instructions 
    Step 1: python3 -m venv fastapienv
    Step 2: source fastapienv/bin/activate

## 2. Install dependencies

Inside the project, run the following CLI commands.
    1. pip3 install fastapi
    2. pip3 install "uvicorn[standard]"

## 3. Run the project

The command for books_v1 is `uvicorn books_v1:app`.

The command for books_v2 is `uvicorn books_v2:app`.

You can now view the project at http://127.0.0.1:8000 

(OR)

You can now view the project at http://127.0.0.1:8000/docs


### 📸 API Response Screenshot

![API Result](images/book-api-result.png)
