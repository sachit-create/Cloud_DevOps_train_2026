# Node Project - Work Notes

## Current Status
- App is running on EC2 at: `http://3.110.132.58:3000/`
- Service responds on `/` with: `Hello from Dockerized Node App`

## Work Completed
- Created a basic Express application in `index.js`
- Configured app to listen on port `3000`
- Added project scripts in `package.json`:
  - `npm start` -> `node index.js`
- Added dependency:
  - `express` (`^5.2.1`)
- Dockerized the application using `Dockerfile`:
  - Base image: `node:18`
  - Working directory: `/app`
  - Installed dependencies with `npm install`
  - Exposed port `3000`
  - Container start command: `npm start`

## Commands Used (Reference)
- Install deps: `npm install`
- Run locally: `npm start`
- Build image: `docker build -t node_project .`
- Run container: `docker run -d -p 3000:3000 --name node_project_app node_project`

## Notes
- Application is currently single-route and can be extended with health/API routes.
- Add `.dockerignore` in next update to reduce build context size.
