# Prometheus & Grafana docker-compose stack

A most simple example project with Prometheus, Alertmanager, Grafana and Node exporter defined via docker-compose. There are some basic alerts configured in Prometheus; Grafana is provisioned with a Node exporter metrics dashboard.

## Prerequisites

Install Docker and docker-compose: https://docs.docker.com/install/

## Deployment

Clone the project, build and run it with docker-compose:

    docker-compose build
    docker-compose up -d

