# TMI Manage


## Prerequisites

1. [Docker Engine](https://docs.docker.com/engine/installation/)
1. [Docker Compose](https://docs.docker.com/compose/install/).


## Installing

From within a command line terminal:
```bash
git clone https://github.com/AfrikaBurn/TMI-Manage.git
cd TMI-Manage
```

## Running

```bash
sudo docker-compose up
```
> This is unsafe in a production environment, follow [these instructions](https://docs.docker.com/engine/security/rootless/) to run the docker daemon in rootless mode!

In rootless mode:
```bash
docker-compose up -d
```
(the -d option starts the Manage server in detached mode)

## Runnig locally

Add the following to your hosts file (/etc/hosts on ubuntu):
```
127.0.0.1 manage.afrikaburn.com
```

Visit: [manage.afrikaburn.com:43000](http://manage.afrikaburn.com:43000)
