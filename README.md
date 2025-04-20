# Static Website – Docker + GitHub Actions CI/CD

This is a simple static website project built to practice DevOps tools and concepts with the help of Chat GPT. The site is containerized using Docker and uses GitHub Actions for CI/CD automation.

## 🔧 Tools Used

- Docker – To containerize the application
- GitHub Actions – To automate building and pushing updates
- HTML/CSS – Static website content

## 🚀 What This Project Does

- Hosts a basic static website inside a Docker container
- Uses a GitHub Actions workflow to:
  - Build the Docker image
  - Push updates automatically when changes are made to the `main` branch

## 🗂️ Project Structure


## 🐳 Docker Instructions

To run locally with Docker:

```bash
docker build -t static-website .
docker run -p 8080:80 static-website
