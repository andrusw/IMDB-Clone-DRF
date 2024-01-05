1) Setup environment:
   python -m venv [virtual environment name]
   example: python -m venv menv

2) Activate env:
   menv\Scripts\activate

3) Install Django:
   go to https://www.djangoproject.com/download/ and get latest pip install version
   pip install Django==5.0.1

4) Upgrade pip
   python -m pip install --upgrade pip

5) Verify packages installed:
   pip freeze

6) Creating a project:
   django-admin startproject [project name]

7) Install extensions in VS Code:
   * Python Extension Pack
   * Tabnine Autocomplete AI
  
8) Create App
   cd [project_name]
   python manage.py startapp [app's name]

9) Add app to project:
   Go to project's folder and open settings.py
   Go to section "INSTALLED_APPS"
   Add app's name to list

10) Migrate:
    Exit the running server if it is running
    Run: python manage.py migrate

11) Create super user:
    python manage.py createsuperuser
    restart the server: python manage.py runserver
    login on server: http://127.0.0.1:8000/admin

12) Create model and views in app
