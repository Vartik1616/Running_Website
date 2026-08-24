# Running Website — DevOps Deployment Project

A lightweight web application used as a practical DevOps project for containerization, CI/CD automation, and Kubernetes deployment.

The project is being developed as part of a hands-on local DevOps laboratory.

---

## Project Overview

This project demonstrates how a simple web application can be packaged into a Docker container and progressively integrated into a DevOps delivery workflow.

The current application consists of:

- HTML
- CSS
- JavaScript
- Docker

The planned DevOps workflow is:

```text
Developer
    |
    v
GitHub
    |
    v
Jenkins
    |
    v
Build & Test
    |
    v
Docker Image
    |
    v
Local Container Registry
    |
    v
Kubernetes
    |
    v
Running Web Application
