# Sample Dockerized Python App

This repository contains a minimal Flask application packaged with Docker.

Quick start

Build the image:

```bash
docker build -t sample-docker-python-app .
```

Run with Docker:

```bash
docker run --rm -p 8000:8000 sample-docker-python-app
```

Or with docker-compose:

```bash
docker-compose up --build
```

Then open http://localhost:8000
