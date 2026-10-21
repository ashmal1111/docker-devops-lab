# Docker DevOps Lab

A Docker Compose application demonstrating a multi-container architecture with:

- Nginx reverse proxy
- Flask backend
- Redis
- Docker Compose networking

## Architecture

Client → Nginx → Flask Backend → Redis

## Services

### Nginx
Acts as a reverse proxy and exposes port 8080.

### Backend
Flask application running on port 5000.

### Redis
Provides Redis service for the backend.

## Run the application

```bash
docker compose up -d --build
