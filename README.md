# Cosmos Startpage
A startpage for Cosmonauts powered by Akash.

## Create Your Own

Prerequisites:
- docker
- docker-compose

To build your own startpage, proceed as follows:
- clone/fork this repository
- customize `docker-compose.yaml` (e.g. image and password).
- run a local instance with `docker-compose up` 
- navigate to http://localhost:5005 and change the startpage to your liking.  
- build and push the Docker image to your own registry
- modify `akash.yaml` to point to your Docker image and domain
- deploy to Akash (e.g. with [Akashlytics Deploy](https://www.akashlytics.com/deploy))
