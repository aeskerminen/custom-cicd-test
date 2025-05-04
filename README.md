# CICD with self-hosted runner test app

## About

This repo is used for testing my self-hosted GitHub actions runner and my ArgoCD instance running on Kubernetes. Testing is done with Cypress.

## How to run locally

docker build -t my-react-app .
docker run -p 3000:80 my-react-app
