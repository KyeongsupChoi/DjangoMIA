## Tools

- [Python 3](https://www.python.org) : The Python Programming Language
- [Django](https://www.djangoproject.com) : The Web Framework for Python
- [TensorFlow](https://www.tensorflow.org) : The TensorFlow Machine Learning Library used to create the neural network

## Setup Instructions

- Download and Install the latest Python 3 on your computer. [Install Now](https://www.python.org/downloads/)


- Create a virtual environment where all packages will be installed.

```bash
# Windows
py -3 -m venv env
# Linux and Mac
python3 -m venv env
```

- Activate the virtual environment.

```bash
# Windows
.\env\Scripts\activate
# Linux and Mac
source env/bin/activate
```

- Install all the required packages.

```bash
pip install -r requirements.txt
```


## Setup Django App

- Create new django project

```bash
# create new project in the current directory
django-admin startproject core .
# run web app
python manage.py runserver
# visit http://localhost:8000/ on your browser
```
