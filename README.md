# MIG (Mosquitto, InfluxDB, Grafana)

MIG is a containerised IoT sensor server stack in the traditions of LAMP and TIG.

This is a Docker Compose collection of containers that implement:

- Mosquitto MQtt broker listening on port 1883 for MQtt message publications

- InfluxDB listening on port 8086 providing a time series database for sensor data storage

- A Mosquitto bridge that listens for MQTT messages and sends contained data to influxDB

- Grafana listening on port 3000 providing a data visualisation environment for sensor data.

Each of these applications is built and runs in its own container.


# Getting going

Install Docker and Docker Compose

Clone this repository

run "docker compose up" in the repository directory

Open your browser to "localhost:3000" to bring up Grafana
username and password are both currently "admin"

It's that easy!

# More detail

VS Code has a docker extension that makes it easy:
 - to bring up the docker composed containers
 - open up a shell in a container
 - stop/start/restart individual containers
 - bring up or down the entire composition of containers



# Maintainer / Contributors

- David Sprague @DaveSprague

# Attribution

- This is in part based on this project:
- - https://github.com/DynamicDevices/ming


# Contributing




