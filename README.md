# Dockerized Flask Starter

A minimal Flask application packaged as a Docker container.

## Why it matters

Docker gives a team a repeatable way to run the same application on a laptop, test server, or cloud platform. This repository is a small demonstration of that deployment foundation.

## What it includes

- A Flask “Hello World” service
- A Dockerfile
- A basic automated test
- A CI/CD workflow example

## Run

```bash
docker build -t flask-starter .
docker run -p 5000:5000 flask-starter
```

Open `http://localhost:5000`.
