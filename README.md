# Monitoring Infrastructure

Infrastructure for setting up multiple monitoring containers behind an NGINX
container.

## The `gitlab-ci.yml` File

This file controls which jobs Gitlab runs for you when pushing.

Currently, the following jobs are defined:

+ `build`: Creates a basic NGINX container at port 8080 with the name `monitoring-base`
