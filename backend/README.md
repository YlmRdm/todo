This project was developed with [Django](https://www.djangoproject.com/).
**Note: First all, you need to write your own password for database from settings.py or ask me**


## Available Scripts..

In the project directory, you can run:

### `python3 -m venv doenv`

Creates the virtual environment in the development mode.<br>

- you can write a different environment name instead of `doenv`

### `source doenv/bin/activate`

Activates the virtual environment in the interactive watch mode.<br>

**Note: Then, Django REST and CORS should be installed in your virtual environment. if installed already, skip the next step.**
- `pip install djangorestframework`
- `pip install django-cors-headers`

### `cd backend`

Changes the directory for django server <br>

### `python manage.py runserver`

Runs the server in the development mode.<br>
Open [http://localhost:8000](http://localhost:8000) to view it in the browser.

**Note: Also, you can see my API.** <br>
Open [http://localhost:8000/todos/api](http://localhost:8000/todos/api) to view it in the browser.
