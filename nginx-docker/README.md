# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
> "The future belongs to those who believe in the beauty of their dreams." - Eleanor Roosevelt
<!-- INSPIRATIONAL_QUOTE_END -->
