# nginx

```bash
$ docker volume create --name http-custom-data
$ cp index.html /var/lib/docker/volumes/http-custom-data/_data/
$ docker run -d -P -v http-custom-data:/usr/share/nginx/html nginx 
```
