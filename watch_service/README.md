# Watch Service

This folder contains the **Watch Service** component of the Thesis YouTube Project. The Watch Service is responsible for tracking and managing user interactions with YouTube videos, such as watch history, playback progress, and analytics.

## Features

- Records user watch events and playback data.
- Provides APIs to retrieve and analyze watch history.
- Integrates with other services in the Thesis YouTube Project ecosystem.

## Technologies Used

- **Nodejs**: The primary programming language for the backend service.
- **Database:** PostgreSQL (via SQLAlchemy ORM)
- **Authentication:** JWT-based authentication
- **Containerization:** Docker

## Folder Structure

- `app/` - Source code for the Watch Service (models, routes, services).
- `tests/` - Unit and integration tests.
- `Dockerfile` - Containerization setup.

## Usage

1. Build and run the service using Docker Compose.
2. Access API endpoints for watch event management.
3. Integrate with other project services as needed.

## Related Documentation

- [Project Overview](../README.md)
