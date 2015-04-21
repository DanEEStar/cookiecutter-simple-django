# {{ cookiecutter.project_name }}

## Setup for development

1. Create a virtualenv for this project

2. Install dependencies:

```
> pip install -r env/requirements/dev.txt
```

3. Kick of initial migration

```
> python manage.py migrate
```

4. Run dev server

```
> python manage.py runserver
```
