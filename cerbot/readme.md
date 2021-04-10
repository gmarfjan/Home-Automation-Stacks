# Creation d'un certif
docker run -ti --rm -v /home/gmarfjan/docker/certbot:/etc/letsencrypt -p 8080:80 certbot/certbot:arm64v8-latest certonly --standalone

# Renouveler un certif
docker run -ti --rm -v /home/gmarfjan/docker/certbot:/etc/letsencrypt -p 8080:80 certbot/certbot:arm64v8-latest renew
