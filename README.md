# Node.js Demo App

A simple Node.js demo app with CI/CD pipeline using GitHub Actions and Docker.

## Run locally

```bash
npm install
npm test
npm start
```

## Docker

```bash
docker build -t nodejs-demo-app .
docker run -p 3000:3000 nodejs-demo-app
```

## CI/CD

The pipeline:
- Runs tests
- Builds Docker image
- Pushes to Docker Hub
```
