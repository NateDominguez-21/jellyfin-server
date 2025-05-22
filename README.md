# Jellyfin Media Server on AWS EC2

This project sets up a self-hosted **Jellyfin** media server on an **AWS EC2** instance using Docker.

---

## Features

- Self-hosted streaming server (Jellyfin)
- Dockerized setup
- Organized media folders for Movies, TV Shows, and Music
- Easy startup script for deployment

---

## Folder Structure
```bash

Inside the container config directory (`/config/root/default/`):

- `Home Videos and Photos/`
- `Movies/`
- `Music Videos/`
- `Shows/`

````

---

## Getting Started

### 1. Clone the Repository

```bash
git clone git@github.com:NateDominguez-21/jellyfin-server.git
cd jellyfin-server
````


## 2. Run the Setup Script
```bash
/setup.sh
   ````

This will:

* Create media folders (movies, tv-shows, music)

* Start Jellyfin using Docker Compose

## 3. Access Jellyfin
Open your browser and visit:
```bash

http://<your-ec2-public-ip>:8096
   ````


To find your EC2 public IP:
```bash

curl http://checkip.amazonaws.com
   ````


Media Folder Paths

./default/movies

./default/tv-shows

./default/music

Simply add your files to these folders and Jellyfin will detect them automatically.

Author

Nathaniel Dominguez

GitHub: @NateDominguez-21

![Docker](https://img.shields.io/badge/Docker-ready-blue?logo=docker)
![AWS EC2](https://img.shields.io/badge/AWS-EC2-orange?logo=amazon-aws)
