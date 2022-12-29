# python-django-web-app
Simple Web Application using Python Django

```python
python -m venv ./devenv
devenv\Scripts\activate.bat
deactivate.bat
> pip freeze > requirements.txt

> devenv\Scripts\activate.bat
pip install django==3.1
pip freeze

# Create a new project
django-admin startproject SimpleCart .

# Run the server
python .\manage.py runserver

python .\manage.py collectstatic

```
