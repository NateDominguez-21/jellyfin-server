# Jellyfin Media Server on AWS EC2

This project sets up a personal Jellyfin media server on an AWS EC2 instance using Docker.

## Features
- Self-hosted streaming server (Jellyfin)
- Dockerized setup
- Media folders for Movies, TV Shows, and Music

## Getting Started

1. Clone the repo:
   ```bash
   git clone git@github.com:NateDominguez-21/jellyfin-server.git

2. Spin it up 

 - docker compose up -d

3. Access Jellyfin: 

 - Visit: `http://<your-ec2-public-ip>:8096` in your browser

Folder Structure 

* /movies 
* /tv-shows
* /music

Author 

Nathaniel Dominguez

![Docker](https://img.shields.io/badge/Docker-ready-blue?logo=docker)
![AWS EC2](https://img.shields.io/badge/AWS-EC2-orange?logo=amazon-aws)
