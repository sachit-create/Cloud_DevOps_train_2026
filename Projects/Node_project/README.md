# Node Docker App

Express-based Node.js application containerized with Docker.

## Project Files

- `index.js`: Application entry point
- `package.json`: Scripts and dependencies
- `Dockerfile`: Container build file
- `work.md`: Work summary and deployment notes

## Run Locally

```bash
npm install
npm start
```

App URL: `http://localhost:3000/`

## Run With Docker

```bash
docker build -t node-project-app .
docker run -d --name node-project-app -p 3000:3000 node-project-app
```

App URL: `http://localhost:3000/`
