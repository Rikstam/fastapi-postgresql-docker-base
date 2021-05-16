# fastapi-postgresql-docker-base

## What

A starting base for a Dockerized FastApi app from https://testdriven.io/blog/fastapi-crud/.

## How

Build and start with `docker-compose up -d --build`.

Run tests with `docker-compose exec web pytest`.

Connect to database `docker-compose exec db psql --username=hello_fastapi --dbname=hello_fastapi_dev`

Shut down the app `docker-compose down -v`
