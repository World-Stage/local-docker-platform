# local-docker-platform
Docker Orchestrator that will spin up Spring Boot API and Nginx Server

Assuming your file structure looks like this:
ROOT
|
| - local Docker Platform
  | - dockercompose.yml
| - backend
  | - nginx-rtmp
    | - nginx.conf
  | - world-stage-api

all you have to do is run docker compose up --build and it should just work!

Spring Boot is on localhost:8082
Nginx is on localhost:8080

You will have to manually run front end. Check out that read me
