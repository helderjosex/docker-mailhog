# Mailhog Docker
This is an official, open-source for Mailhog based projects that run on Docker-Compose. 
    
## Usage
You are up and running in three simple steps:

$ cd mailhog-docker

$ docker-compose up --build -d 
 
You can just open your browser at:

http://localhost:8025 or you can get the container IP: docker inspect CONTAINER ID | grep IPAddress

To use the CLI to access mailhog directly execute the following:

$ docker exec -it mailhog
