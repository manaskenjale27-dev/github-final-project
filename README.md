# CI/CD Final Project

Project: CI/CD Tools and Practices Final Project

This repository demonstrates continuous integration and continuous delivery using GitHub Actions, Tekton, and OpenShift Pipelines.

## CI workflow
The GitHub Actions workflow runs dependency installation, code linting with flake8, and unit tests with nose.

## Tekton pipeline
Tekton tasks include workspace cleanup and automated unit tests using nose.

## OpenShift deployment
The application is deployed to OpenShift and listens on port 8000 when the application container is running.
