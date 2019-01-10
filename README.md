# lizmap-stack-docker
I wanted to revamp my website (officinecartografiche.net) with some services:
* static website
* pelican blog
* lizmap
* postgis

all served with subdomains
Following this [DigitalOcean tutorial](https://www.digitalocean.com/community/tutorials/how-to-use-traefik-as-a-reverse-proxy-for-docker-containers-on-ubuntu-18-04)

I set up [traefik] (https://traefik.io/)a modern reverse proxy to easily manage subdomains.

I pulled [jancelin/docker-lizmap] (https://github.com/jancelin/docker-lizmap) docker-compose repo on my github and started playing around in order to:
* set traefik labels
* use nextcloud insted of [cloudcmd] (http://cloudcmd.io/) (probably the worng choice)
for the moment it's up and running!

What I need to do:
1. find out how to upload file into Lizmap project folder usign nextcloud
2. test lizmap with a sample [project] (https://github.com/jancelin/docker-lizmap/tree/master/files/qgis)
3. parameters tune up

SUGGESTIONS ARE WELCOME
