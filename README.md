# DAVIT ERPNEXT
 about [Frappe](https://github.com/frappe/frappe) and [ERPNext](https://github.com/frappe/erpnext) in containers.

![GitHub tag](https://img.shields.io/github/v/tag/davittec/davit_erpnext?label=version)
![GitHub repo file or directory count](https://img.shields.io/github/directory-file-count/davittec/davit_erpnext)



## Getting Started

To get started you need 

- [Docker](https://docs.docker.com/get-docker/),
-  [docker-compose](https://docs.docker.com/compose/), and 
- [git](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git) setup on your machine. 

General Documentation

- refer to Docker's [documentation](http://docs.docker.com).

### Setup

This is based on a single server setup, similar to the instructions provide be Frappe Docker [single server example⁠](https://github.com/frappe/frappe_docker/blob/main/docs/single-server-example.md). 

In this example we a singel service with a statis IP attached to ERPNext runtime. 

We nee to install the following:

- [ ] [Install docker](#Install Docker) and docker compose v2 on linux server.
- [ ] [Clone frappe_docker](#Clone frappe_docker) repo 
- [ ] [Install traefik](#Install traefik) service for internal load balancer and letsencrypt.
- [ ] Install MariaDB with containers.
- [ ] Setup project called `erpnext-one` and create sites `one.example.com` and `two.example.com` in the project.

Start by cloning this repository

```bash
git clone https://github.com/DavitTec/davit_erpnext.git
```

### Install Docker

```bash
docker version
# Version:           27.0.3
docker compose version
# Docker Compose version v2.28.1

```

### Clone frappe_docker

Clone `frappe_docker` repo for the needed YAMLs and change the current working directory of your shell to the cloned repo.

```
git clone https://github.com/frappe/frappe_docker
cd frappe_docker
```

### Install traefik

## [Changelog](CHANGELOG.md)

## References
