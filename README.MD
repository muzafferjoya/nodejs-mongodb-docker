
# Docker Compose Nodejs and MongoDB Application

## Node.js Express and MongoDB with Docker Overview

Assume that we have a Nodejs Application working with MongoDB database.
The problem is to containerize a system that requires more than one Docker container:


- Node.js Express for API
- MongoDB for database

### We’re gonna following these steps:

- Create Nodejs App working with MongoDB database.
- Create Dockerfile for Nodejs App.
- Write Docker Compose configurations in YAML file.
- Set Environment variables for Docker Compose
- Run the system.

### Run Nodejs MongoDB with Docker Compose

```bash
docker-compose up -d
docker-compose ps
```