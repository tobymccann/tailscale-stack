# Tailscale VPN Container

## How to use
This repository is intended to be deployed using Portainer into a Docker environment. This can be done by creating a new Portainer stack. Note that running this container will have a similar result to installing Tailscale on the host machine.

When creating the stack in Portainer, add an environment variable named `SECRET_AUTH_KEY`. This variable should contain the Tailscale key which allows the client to connect to the network. Click on the image below to see a larger version.

![](img/screenshot1.png)

I use reusable Tailscale auth keys for this application.

![](img/screenshot2.png)

**Tested on Portainer 2.17.1 and Docker 23.0.1, build a5ee5b1**

For more information on Tailscale, visit [tailscale.com](https://tailscale.com/).