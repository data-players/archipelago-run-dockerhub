# archipelago-run-dockerhub

The easiest way to deploy an archipelago prepared by Data Players with few customisation thing ! 

## Data Players personnalisation

- deployement by DockerHub images build thanks to https://github.com/data-players/archipelago-build-dockerhub
- Reified Relation betwen user, organstion with role

## Introduction (for production)

First make sur you get docker, docker-compose and git install on your linux server.
Make sure you have an usable domain name, then create 3 sub-domain :
- middleware (Exemple : data.myDomain.com)
- frontend (Exemple : myDomain.com)
- authentification (Exemple login.myDomain.com)(optional if you use sso and want domain login with same root than your app)

## usage
same usage than https://github.com/data-players/deploy-archipelago-classic
