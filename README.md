# How to use this example
A short example about how to use [traefik](https://hub.docker.com/_/traefik). 
## Installation
This example includes a configuration file called *traefik.toml*, where a network is declared which is used by traefik. In my case this network is called "traefik-global-proxy", which has to be created before startup, i.e.

``docker network create traefik-global-proxy``.

Afterwards, simply run the included docker-compose file

``docker-compose up -d``.

