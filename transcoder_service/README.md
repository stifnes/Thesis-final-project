# Transcoder Service

This folder contains the source code and configuration files for the **Transcoder Service** component of the Thesis YouTube Project.

## Overview

The Transcoder Service is responsible for processing and converting video files into various formats and resolutions suitable for streaming or download. It automates the workflow of receiving raw video uploads, transcoding them, and storing the processed outputs for further use within the project.

## Features

- **Automated Video Transcoding:** Converts uploaded videos into multiple formats (e.g., MP4, WebM) and resolutions (e.g., 1080p, 720p, 480p).
- **Queue-based Processing:** Handles multiple transcoding jobs efficiently using a job queue.
- **Error Handling and Logging:** Provides detailed logs and error reporting for monitoring and debugging.
- **API Integration:** Exposes endpoints or interfaces for other services to submit transcoding jobs and retrieve results.

## Technologies Used

- **Programming Language:** Node.js
- **Transcoding Library:** [FFmpeg](https://ffmpeg.org/) for video and audio processing
- **Task Queue:** Kafka
- **Storage:** Local filesystem, AWS S3
- **Containerization:** Docker for consistent deployment environments

## Folder Structure

```
transcoder_service/
├── hls/                # Source code for the transcoder service
├── Dockerfile          # Containerization setup
├── README.md           # Project documentation
└── ...                 # Additional scripts and resources
```

## Usage

- Submit a video file via the provided API or interface.
- The service processes the file and outputs transcoded versions.
- Access the processed files from the configured storage location.
