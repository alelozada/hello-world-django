# Django Hello World

1. Install a virtual enviroment
    
    py (or python o python3) pip install --upgrade pip && 
    py -m venv .venv
    
2. Created a requirements.txt

    add requests inside the file
    add the Django version inside the file (Django==3.2 for example)
    
3. Initialize the Django project

    django-admin startproject app
    
4. Install the core in the projects

    py app/manage.py startapp core
    
 5. You can start the server with the next command
 
  py app/manage.py runserver
