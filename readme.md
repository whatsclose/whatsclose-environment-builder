# Architecture

## Technical components
- NATS container
- ES container
- ES Volume
- SQLite Volume per service
- Reddis container
- Reddis volume

## Usage
- .env file contains variables needed to setup the services
- Dev environment set in docker-compose.override.yml
- docker-compose.yml and docker-compose.override.yml automatically used with `docker-compose up` command
- Use of a volume plugin to persist global named volumes
https://github.com/CWSpear/local-persist

