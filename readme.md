# Home Automation Stacks

This repository lists all Docker stacks used on my home automation system, based on arm64.

I use portainer for managing stacks.

# Installing Portainer

Please change /path/to/home_dir to portainer configuration directory.

```
docker run -d -p 8000:8000 -p 9000:9000 --name portainer --restart=always --log-driver json-file --log-opt max-file=2 --log-opt max-size=100m -v /var/run/docker.sock:/var/run/docker.sock -v /path/to/home_dir:/data portainer/portainer-ce:latest
```
