# Server Boilerplates

This is a repository of docker-compose boilerplates for common vps setup and web deployments.

## What is included?

1. Traefik - Reverse Proxy
2. Portainer - Container Management
3. Postgres - Database
4. Redis - Cache
5. PGAdmin - Database Management
6. Minio - Object Storage
7. Projects - Place holder for your projects

## Prerequisite

All docker compose files referrence external networks named `frontend` and `database`. You will need to create these networks before running the docker compose files.

## Usage

1. Install Docker.
2. Clone this Repository.
3. Goto Traefik Folder and run `docker-compose up -d`.
4. Goto Portainer Folder and run `docker-compose up -d`.
5. Deploy the rest of the applications using portainer UI.
