![CI/CD Status Badge](https://github.com/troclaux/learn-cicd-starter/actions/workflows/ci.yml/badge.svg)

# Note-Taking App: CI/CD Learning Project

> A note-taking application to learn CI/CD using Docker, GitHub Actions, and Google Cloud Platform (GCP)

This project focuses on implementing a CI/CD pipeline with Github Actions that builds a Docker image and pushes it to GCP's [Artifact Registry](https://cloud.google.com/artifact-registry).

[Link to deployed application](https://notely-83112333672.us-central1.run.app/)

## Project Objectives

1. Learn CI/CD Concepts:
   - Understand how to create and automate workflows for continuous integration and delivery.
   - Familiarize yourself with tools like Docker, GitHub Actions, and GCP.

2. Implement a Full CI/CD Pipeline:
   - Automate building, testing, and deployment processes.
   - Push Docker images to a cloud-based artifact repository.

3. Deploy a Production-Ready Application:
   - Configure and deploy to a GCP compute instance or similar service.

## Key Features

- Automated Workflows: Leverage GitHub Actions for CI/CD automation.
- Cloud Integration: Use GCP Artifact Registry for storing and managing Docker images.
- Scalable Deployment: Deploy the app on GCP with a containerized approach.

## Tasks and Steps

### CI/CD Implementation Tasks

- [x] Workflow Creation: Program a workflow in GitHub Actions to:
  - [x] Build and test the application.
  - [x] Build a Docker image.
  - [x] Push the Docker image to GCP’s Artifact Registry.
- [x] Artifact Registry Setup:
  - [x] Create and configure a repository in GCP's Artifact Registry.
- [x] Verify the workflow executes correctly and CI/CD is functioning as expected.

### Typical CI/CD Workflow Steps

1. Setup:
   - Clone the repository to the runner.
   - Install necessary dependencies (e.g., Go, Node.js, or other tools).

2. Build:
   - Compile/build the application.
   - Build a Docker image.

3. Deploy:
   - Authenticate with the cloud provider (GCP in this case).
   - Configure the cloud provider’s CLI tools.
   - Deploy the application to a compute instance.

## Tools

- Golang
  - Goose
  - Turso
- Github Actions
- Docker
- Google Cloud Provider
  - Google SDK
  - Artifact Registry
  - Cloud Run

## Helpful Links

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Docker Documentation](https://docs.docker.com/)
- [GCP Artifact Registry Documentation](https://cloud.google.com/artifact-registry/docs)
