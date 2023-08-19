# Open Your Terminal:
`python3 --version`
`pip install virtualenv`
<!-- Create a Virtual Environment: -->
`virtualenv venv`
# Activate the Virtual Environment:
venv\Scripts\activate
    'or'
`source venv/bin/activate`

# Install Dependencies:
`pip install django`

# Create and Work on Your Django Project:
`django-admin startproject projectname .`
`cd projectname`
`python manage.py createsuperuser`
  <!-- if not working troubleshoot -->
  `python manage.py migrate`
  [`django start`]
`python manage.py runserver`
Open a web browser and go to `http://127.0.0.1:8000/admin/`.

<!-- create a django app -->
`python manage.py startapp nameofapp`
# python image process libery
`pip install pillow`

`python manage.py makemigrations`


# Deactivate the Virtual Environment:
`deactivate`

