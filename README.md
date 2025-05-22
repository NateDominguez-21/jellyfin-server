# Jellyfin EC2 Media Server

This is a self-hosted media server built with Jellyfin running on an AWS EC2 instance using Docker Compose. It organizes and streams movies, TV shows, and music from the cloud.

## Tech Stack
- **Jellyfin** for media management
- **Docker Compose** for container orchestration
- **AWS EC2** for cloud hosting
- **Ubuntu** for the server OS

## Setup Instructions

```bash
# Clone the repo
git clone https://github.com/NateDominguez-21/jellyfin-server.git
cd jellyfin-server

# Start the container
docker compose up -d
