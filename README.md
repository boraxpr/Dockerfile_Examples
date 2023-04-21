# Dockerfile_Examples
A docker compose that starts a microservice gateway, 2 microservices.

### Prerequisite
1. Installed Elasticsearch
2. Installed Kibana
3. Installed Fleet
4. Installed Elastic Agent
5. Eureka Registry server for port 8761
6. A backend microservice for port 8081
7. A backend microservice for port 8082
8. Installed Docker and Docker compose

### What does it do ?
1. `docker compose up` to start a registry gateway, 2 microservices and elastic agents attached to both microservices.
2. Now every request will appear on Kibana for monitoring purposes.
