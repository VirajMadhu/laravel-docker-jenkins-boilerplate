# Laravel Boilerplate with Docker and Jenkins

This repository contains a Laravel boilerplate designed to work seamlessly with Docker for containerized environments and Jenkins for CI/CD pipelines.

## Features
- **Laravel 10.x**: Latest version of Laravel.
- **Docker**: Containerized environment for easy local development.
- **Jenkins**: Pre-configured for CI/CD with sample pipeline script.
- **Nginx and MySQL**: Dockerized setup includes Nginx as the web server and MySQL as the database.
- **Composer**: Integrated with Docker for package management.
- **Node.js and NPM/Yarn**: Front-end assets and dependencies handled in the Docker setup.
- **.env**: Customizable environment variables for both local development and production.

---

## Prerequisites
Before you begin, make sure you have the following installed:
- Docker
- Docker Compose
- Jenkins (optional: if setting up CI/CD locally)
- Node.js (optional: only if not using the Docker container for frontend)

---

## Getting Started

- Clone the repository

```bash
git clone https://github.com/VirajMadhu/laravel-docker-jenkins-boilerplate.git
cd laravel-docker-jenkins-boilerplate
```

- run docker composer 
```shell
docker compose up
```

- Create laravel project

```shell
./bin/create-laravel-project.sh <project-name> <laravel-version>
```


