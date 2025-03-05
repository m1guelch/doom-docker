Containerized Doom game playable on the web browser
==================

This repository provides the code needed to deploy a self-hosted Doom-game app that can be played on the web browser.
The `/doom` directory contains the actual web app that runs doom via JS-DOS on a webserver.


# Prerequisites

You only need to have Docker and Docker compose installed on your server in order to run the Doom app.


# Usage
1. Clone this repository
2. Deploy the container
3. Access the game on your web browser


## 1. Clone this repository

You can do so running this command in the working directory of your choice:

```
git clone https://github.com/m1guelch/doom-docker.git
```


## 2. Deploy the container

To run the container, execute the following command inside of the repository directory:

```
docker-compose up -d
```

You can check if the container is running correctly by executing this command:

```
docker ps
```


## 3. Access the game on your web browser

Doom should now be playable on http://<YOUR-IP-ADDRESS>:8085 on any web browser of your choice. Enjoy!