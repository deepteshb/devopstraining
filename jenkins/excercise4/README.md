# Excercise 3
## Create a pipeline to store the artifact which is a docker image in the nexus repository.
### Pre-Requisite
- Sonarqube server running
- Docker installed on jenkins master
- Webhook Configured on Sonarqube to send status back.
- Docker Registry (Private or Public ) shall be created and available.

1. The challenge is to have 2 docker containers 1 for jenkins and 1 for sonarqube
2. Setup a Jenkins scripted pipeline for executing the following stages.
    - Checkout
    - Build
    - Static Code Analysis
    - Quality Gate Check Status
    - Containerize
    - Push Image
