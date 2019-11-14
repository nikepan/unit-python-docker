# unit-python docker image
Nginx Unit with python 3.7 docker image

[Original](https://github.com/nginx/unit/blob/master/pkg/docker/Dockerfile.python3.5) image file supports python 3.5

This image supports newer Python and use Alpine linux.
Configuring same as orignial image:
https://unit.nginx.org/installation/

```Dockerfile
COPY ./*.pem  /docker-entrypoint.d/
COPY ./*.json /docker-entrypoint.d/
COPY ./*.sh   /docker-entrypoint.d/
```
or mount /docker-entrypoint.d/
