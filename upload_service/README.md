# Upload Service

This folder contains the **Upload Service** for the Thesis YouTube Project. The service is responsible for handling video uploads, processing, and integration with YouTube's API.

## What It Does

- Accepts video files from users or other services.
- Validates and processes video metadata.
- Handles authentication and communication with the Video Data API.
- Manages upload status, error handling, and logging.
- Provides RESTful endpoints for upload operations.

## Technologies Used

- **Nodejs**: Core programming language for the service.
- **Docker**: Containerization for deployment and development.

## Folder Structure

- `app/`: Main application code.
- `Dockerfile`: Container configuration.
- `README.md`: Project documentation (this file).

## Getting Started

1. Clone the repository.
2. Install dependencies: `npm install`
3. Set up environment variables for API credentials.
4. Run the service: `npm run devstart` or use Docker.
