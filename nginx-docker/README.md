# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
> "It's not whether you get knocked down, it's whether you get up." - Vince Lombardi
<!-- INSPIRATIONAL_QUOTE_END -->
