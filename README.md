# refarch
Clone of redbook SG24-8351 Hybrid Cloud Architecture rep

This repository created to upgrade the MQ and IIB versions in the Docker containers.

Welcome

This is the repository for all resources on Scenario 3 for the IBM RedBooks publication A practical guide to hybrid integration.

Docker config

Follow the steps below to recreate the scenario environment on your own docker host. For this to work you need to have both docker and docker-compose installed and working.

Clone the repository
Open a shell and navigate to the scenario1 directory
Run the docker-compose up -d command
Afterwards there should be 3 containers running with the following names:

mq
iib-op
sgc
Verify which containers are running with the docker-compose ps command ran in the same directory location.
