# Create a certificate
```
docker run -ti --rm -v /path/to/cert_dir:/etc/letsencrypt -p 8080:80 certbot/certbot:arm64v8-latest certonly --standalone
```

# Renew a certificat
```
docker run -ti --rm -v /path/to/cert_dir:/etc/letsencrypt -p 8080:80 certbot/certbot:arm64v8-latest renew
```
