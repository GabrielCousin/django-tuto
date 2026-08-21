# Django-tuto

## Install

```sh
$ brew install uv
$ uv sync
```

## Commands

```sh
# Start server
$ uv run python manage.py runserver

# Migrate database
$ uv run python manage.py migrate

# Create database migration
$ uv run python manage.py makemigrations [app]

# Get SQL for a given migration
$ uv run python manage.py sqlmigrate [app] [migration_name]

# Open a Django shell
$ uv run python manage.py shell

# Run tests
$ uv run python manage.py test [app]

# Create app
$ uv run python manage.py startapp [app]
```

## Gotchas

- [urls.py](https://docs.djangoproject.com/en/6.1/topics/http/urls/)
- [Django shortcut functions](https://docs.djangoproject.com/en/6.1/topics/http/shortcuts/)
- [Built-in template tags and filters](https://docs.djangoproject.com/en/6.1/ref/templates/builtins/)
- Debug toolbar requires a body HTML tag to work as expected

## Out of scope

- [Setup other DB](https://docs.djangoproject.com/en/6.1/topics/install/#get-your-database-running)

## WTF?

- [WSGI](https://wsgi.readthedocs.io/en/latest/what.html)
- Testing: assert versus self.assert*
- https://stackoverflow.com/questions/58789733/how-to-make-drf-hyperlinkedmodelserializer-elegantly-work-with-app-name
