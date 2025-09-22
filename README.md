# Node.js Demo App

A simple Node.js demo app with CI/CD pipeline using GitHub Actions and Docker.

## Run locally

```bash
npm install
npm test
npm start
```

<img width="1916" height="998" alt="image" src="https://github.com/user-attachments/assets/21c32851-c326-46a8-9b41-22dad45a2202" />


## Docker

```bash
docker build -t nodejs-demo-app .
docker run -p 3000:3000 nodejs-demo-app
```

<img width="1919" height="1006" alt="image" src="https://github.com/user-attachments/assets/094d95ac-6cff-4545-9728-ba9be0eee325" />


## CI/CD

The pipeline:
- Runs tests
- Builds Docker image
- Pushes to Docker Hub

