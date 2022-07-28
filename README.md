# Cosmos Startpage
A startpage for Cosmonauts powered by Akash.  
See it in action here: https://cosmos.dcentral.systems/

## Create Your Own

Prerequisites:
- docker
- docker-compose
- akash-cli or [Akashlytics Deploy](https://www.akashlytics.com/deploy)

To build your own startpage, proceed as follows:
- clone/fork this repository
- customize `docker-compose.yaml` (e.g. image and password).
- run a local instance with `docker-compose up` 
- navigate to http://localhost:5005 and change the startpage to your liking.  
- build and push the Docker image to your own registry
- modify `akash.yaml` to point to your Docker image and domain
- deploy to Akash
