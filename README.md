# README: CI/CD Pipeline for Full-Stack Application

## Project Description

This project integrates a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a full-stack application. The pipeline ensures clean and reliable code integration by running Cypress component tests during Pull Requests to the develop branch and deploying the application to Render when changes are merged to the main branch.

## Setup

### Install Dependencies

```bash
npm install
```

### Configure Secrets in GitHub

- RENDER_DEPLOY_HOOK: Render Deploy Hook URL.
- RENDER_API_KEY: Render API Key.
- Deploy to Render

Initial manual deployment from main.
Turn off Auto-Deploy in Render and copy the Deploy Hook URL.
Create GitHub Actions Workflows

### Place YAML files in .github/workflows/:

- cypress-tests.yml (testing)
- deploy-to-render.yml (deployment)

## Scripts

Run Cypress Tests Locally:

```bash
npm run test:cypress
```

Render Link: [Application Link](https://two0-github-actions-0m3k.onrender.com)

Author
Judymae Jolibois

- [Judymae Jolibois' Github](https://two0-github-actions-0m3k.onrender.com)
