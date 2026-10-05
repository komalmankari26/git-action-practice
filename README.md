[![Docker Publish](https://github.com/komalmankari26/git-action-practice/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/komalmankari26/git-action-practice/actions/workflows/docker-publish.yml)
# GitHub Actions Practice

90 Days of 
---

# GitHub Actions CI/CD Capstone

A production-oriented CI/CD pipeline demonstrating automated testing, reusable GitHub Actions workflows, Docker image publishing, deployment flow, and container health monitoring.

## Application

A lightweight Flask application with:

- `/` — application status
- `/health` — health check endpoint
- Automated pytest tests
- Docker containerization

## Local Application

Run the application:

```bash
pip install -r requirements.txt
python app.py