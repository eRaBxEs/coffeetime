# Getting Started with Docker-Compose

This project was created to use docker-compose 

## Available Scripts

In the project directory, after cloning and installing docker-compose, you can run the following:

### `sudo docker-compose up -d` to start the containers in the docker-compose in the background
### `sudo docker-compose ps` to inspect the containers running in the docker-compose


Once up it runs 2 nginx websites servers, one on a localhost and one on a given network
Open [http://localhost:8081][http://192.168.92.21] to view each of them in your browser.

To stop the running servers , use this:
### `sudo docker-compose stop` to stop the containers in the docker-compose

To bring down the containers, use this:
### `sudo docker-compose down` to bring down the containers in the docker-compose
