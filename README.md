# Amazon Linux 2 Image

[![CI](https://github.com/PedigreeTechnologies/docker-amazonlinux2-base/workflows/Build/badge.svg?branch=master&event=push)](https://github.com/PedigreeTechnologies/docker-amazonlinux2-base/actions?query=workflow%3ABuild) [![Docker pulls](https://img.shields.io/docker/pulls/PedigreeTechnologies/docker-amazonlinux2-base)](https://hub.docker.com/r/pedigreetechnologies/docker-amazonlinux2-base)

Amazon Linux 2 Docker container.

## Tags

- `latest`: Latest successful build of the Amazon Linux 2 container.

## How to Build

This image is built on Docker Hub automatically any time the upstream OS container is rebuilt, and any time a commit is made or merged to the `master` branch. But if you need to build the image on your own locally, do the following:

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. Clone this repo locally on your machine.
  3. `cd` into the root repo directory.
  4. Run `docker build -t amazonlinux2-base .`

## How to Use

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. Pull this image from Docker Hub: `docker pull pedigreetechnologies/docker-amazonlinux2-base:latest` (or use the image you built earlier, e.g. `amazonlinux2-ansible:latest`).
  3. Run a container from the image: `docker run --detach --privileged  pedigreetechnologies/docker-amazonlinux2-base:latest`

## Author

Originally created in 2018 by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
Adapted for internal use at Pedigree Techologies in 2022
