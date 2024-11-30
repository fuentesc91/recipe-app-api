# recipe-app-api

## Base command

docker compose run --rm app sh -c

## Lint with flake8

docker compose run --rm app sh -c "flake8"

## Run tests

docker compose run --rm app sh -c "python manage.py test"