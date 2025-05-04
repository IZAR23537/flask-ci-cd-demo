# Flask CI/CD Demo

This is a simple Flask app to demonstrate a CI/CD pipeline using GitHub Actions and Docker.

## Features

- Flask web app
- Unit testing with `unittest`
- Dockerized deployment
- GitHub Actions CI/CD workflow

## Run locally

```bash
docker build -t flask-ci-cd-demo .
docker run -p 5000:5000 flask-ci-cd-demo
```

## Test locally

```bash
python -m unittest discover tests
```
