# local-docker-platform

Docker Orchestrator that will spin up a Spring Boot API and Nginx Server.

## File Structure

```
ROOT
├── local-docker-platform
│   └── dockercompose.yml
├── backend
│   ├── nginx-rtmp
│   │   └── nginx.conf
│   └── world-stage-api
```

## Getting Started

To get everything running, simply execute the following command from the root directory:

```
docker compose up --build
```

## Services

- **Spring Boot API**: http://localhost:8082  
- **Nginx (RTMP server)**: http://localhost:8080

## Frontend

You will need to manually start the frontend. Check out the README.md in the frontend directory for more details.
