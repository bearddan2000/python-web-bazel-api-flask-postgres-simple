# python-web-bazel-api-flask-postgres-simple

## Description
Creates an api of `dog` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.

## Tech stack
- bazel
- python
- flask

## Docker stack
- l.gcr.io/google/bazel:latest
- postgresql

## To run
`sudo ./install.sh -u`
- Get all dogs: http://localhost/dog
  - Schema id, breed, and color
- Query with params: http://localhost/dog <id>

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
