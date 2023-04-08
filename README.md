# Argus
Continuous monitoring solution that aggregates data from multiple SAST, DAST, SCA, and dependency scanner solutions, retrieves repository information and correlates it with an organizations APM (Application Porfolio Management) or CMDB (Configuration Management Database) solution)

### Running in Local Environment
To test locally, cd into and use the docker compose located in [assets/docker](assets/docker).

It is recommended that you start a separate terminal window to perform the following steps;
```buildoutconfig
cd assets/docker
docker-compose up -d --build                        # builds grafana and postgres docker images
```