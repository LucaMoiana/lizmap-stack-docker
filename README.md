# lizmap-stack-docker
I wanted to revamp my website (officinecartografiche.net) with some services:
* static website
* pelican blog
* lizmap
* postgis

all served with subdomains
~~Following this [DigitalOcean tutorial](https://www.digitalocean.com/community/tutorials/how-to-use-traefik-as-a-reverse-proxy-for-docker-containers-on-ubuntu-18-04)~~
Moved everything to Hetzner [https://www.hetzner.com/] and got a domain name on OVH [https://www.ovh.com/]

I set up [Caddy Server 2] (https://caddyserver.com/) a reverse proxy to easily manage subdomains.

I pulled [jancelin/docker-lizmap] (https://github.com/jancelin/docker-lizmap) docker-compose repo on my github and started playing around in order to adapt the general concept to my website


What I need to do:

~~1. find out how to upload file into Lizmap project folder usign nextcloud~~
~~2. test lizmap with a sample [project] (https://github.com/jancelin/docker-lizmap/tree/master/files/qgis)~~

3. parameters tune up
4. create a landing page
5. import old blog post in Pelican
6. assess the need of a postgis DB
7. use redis to speed up services

Docker-compose list:
Caddyserver
Portainer
Nextcloud
Postgis
Lizmap
QgisServer
Redis

SUGGESTIONS ARE WELCOME
