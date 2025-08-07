# My Node.js CI/CD App 🚀

This is a simple Node.js web application that returns a "Hello from CI/CD Pipeline!" message.

It demonstrates how to:
- Build a basic Node.js server
- Use Docker to containerize the app
- Set up a CI/CD pipeline with GitHub Actions
- Push Docker images to DockerHub

---
# Project Structuremy-node-app/
├── index.js # Main server file
├── package.json # Project config and dependencies
├── Dockerfile # Instructions to build Docker image
├── .dockerignore # Files Docker should ignore
└── .github/
└── workflows/
└── main.yml # GitHub Actions CI/CD workflow

## 🖥️ How to Run Locally (Without Docker)

```bash
npm install
npm start
Then visit: http://localhost:3000

