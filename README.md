## lunchpicker-miniproject-docker-compose

**Prerequisites:**
- Docker
- Java 17
- Node 20

1. Place the docker-compose.yml at the root of two project files
  ```bash
  /mini-projects/
  /lunch-selector/
    /...
    Dockerfile
  /lunchpicker/
    /...
    Dockerfile
  docker-compose.yml
  ```
  
2. Run docker-compose from directory
  ```bash
  docker-compose up --build
  ```
