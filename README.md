# docker-nginx-alpine
Nginx Alpine Docker File

# Usage
```
$ docker run -p 80:80 -p 443:443 -v <docker_volume_name>:/var/log/nginx -v <docker_volume_name>:/usr/share/nginx -v <docker_volume_name>:/usr/share/nginx uretgec/nginx-alpine
```

# Many many Thanks
- https://github.com/nginxinc/docker-nginx
