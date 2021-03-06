# docker_circuitjs1
Docker image for CircuitJS1 (Electronic Circuit Simulator in the Browser) - https://github.com/sharpie7/circuitjs1

## Running
### Docker CLI

    docker run --restart=unless-stopped -d \
        -p 8080:80 \
        --name=circuitjs1 \
        jorisl42/docker_circuitjs1
### Docker Compose
    circuitjs1:
      image: "jorisl42/docker_circuitjs1"
      container_name: circuitjs1
      restart: unless-stopped
      ports:
        - "8080:80"

## Usage
Open [http://localhost:8080](http://localhost:8080) in the browser.

## Links
- [Github repo](https://github.com/JorisL/docker_circuitjs1)
- [Docker Hub](https://hub.docker.com/r/jorisl42/docker_circuitjs1)
- [CircuitJS1](https://github.com/sharpie7/circuitjs1)
