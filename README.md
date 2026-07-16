# Future Tech Leaders Docker Compose Deployment

## Overview

This project is a containerized deployment of the Future Tech Leaders website using Docker and Docker Compose. The application is a Next.js website that runs on Node.js and uses Supabase configuration through environment variables.

The goal of this project was to practice inspecting an existing application, understanding its runtime requirements, building a Docker image, running it with Docker Compose, and validating that the deployment works.

## Technologies Used

- Docker
- Docker Compose
- Node.js
- Next.js
- React
- TypeScript
- Supabase
- Git and GitHub

## What I Did

- Cloned and inspected the project structure.
- Identified the application as a Next.js/Node.js project by reviewing `package.json`.
- Reviewed the `Dockerfile` and `docker-compose.yml`.
- Built the Docker image using Docker Compose.
- Started the application as a containerized service.
- Verified the site in the browser at `http://localhost:3001`.
- Used `docker compose ps`, `docker compose logs`, and `curl` to validate the deployment.
- Fixed a production image optimization warning by adding the `sharp` dependency.
- Removed local environment files and build output from Git tracking.

## How To Run Locally

Go into the application folder:

```bash
cd future-tech-leaders-website
