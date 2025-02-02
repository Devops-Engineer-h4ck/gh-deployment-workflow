# GitHub Deployment Workflow

## Project Overview
This repository contains a GitHub Actions workflow that automates the deployment of a static website to **GitHub Pages**. The workflow is triggered only when changes are made to the `index.html` file.

## Solution
- A **GitHub Actions workflow** is defined in `.github/workflows/deploy.yml`.
- The workflow triggers on pushes to the `main` branch where `index.html` is modified.
- The website is deployed to **GitHub Pages**, making it accessible via:
  ```
  https://<username>.github.io/gh-deployment-workflow/
  ```
- This ensures an automated and efficient **CI/CD** process for deploying static web content.

## Usage
1. Modify `index.html` and push changes to `main`.
2. The workflow will run and deploy the updated file.
3. Visit the GitHub Pages URL to see the changes.

## Technologies Used
- **GitHub Actions**
- **GitHub Pages**
- **CI/CD Automation**

---
Simplified and efficient deployment process for static websites. 🚀

