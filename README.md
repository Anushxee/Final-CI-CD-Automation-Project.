# CI-CD Final Project

## Project Overview

This project demonstrates the implementation of a complete Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions, Tekton Pipelines, and OpenShift.

## Features

- Continuous Integration using GitHub Actions
- Code quality checks using Flake8
- Automated unit testing using Nose
- Container image build using Buildah
- Deployment to OpenShift
- Tekton pipeline automation

## Project Structure

```
.
├── .github
│   └── workflows
│       └── workflow.yml
├── .tekton
│   └── tasks.yml
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
```

## CI/CD Workflow

1. Clone repository
2. Run Flake8 linting
3. Execute Nose unit tests
4. Build container image
5. Deploy application to OpenShift

## Technologies Used

- Python
- GitHub Actions
- Tekton
- OpenShift
- Buildah
- Docker
