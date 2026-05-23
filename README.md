![Deploy](https://github.com/nnaji-kenechi/mesut-ride-app/github/workflows/deploy.yml/badge.svg)

# CI/CD Website Deployment Project

## Project Overview
This project demonstrates how to build and deploy a static website using a CI/CD pipeline.

The website was developed using HTML and CSS and deployed to an AWS EC2 Ubuntu server using GitHub Actions for automation.

---

## Technologies Used

- HTML5
- CSS3
- Git & GitHub
- GitHub Actions
- AWS EC2
- Nginx
- Ubuntu Server

---

## CI/CD Pipeline Flow

1. Developer pushes code to GitHub
2. GitHub Actions automatically detects changes
3. Workflow runs deployment process
4. Files are deployed to AWS EC2 server
5. Nginx serves the updated website

---

## Project Structure

```bash
project-folder/
│
├── index.html
├── style.css
├── script.js
└── .github/
    └── workflows/
        └── deploy.yml
