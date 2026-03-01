# Flask Docker App

Simple Flask application containerized with Docker.

## Project Files

- `app.py`: Flask entry point
- `requirements.txt`: Python dependencies
- `Dockerfile`: Container build file

## Run Locally (Without Docker)

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

App URL: `http://localhost:5000/`

## Run With Docker

```bash
docker build -t flask-docker-app .
docker run -d --name flask-docker-app -p 5000:5000 flask-docker-app
```

App URL: `http://localhost:5000/`
