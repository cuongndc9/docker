# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
> "We may encounter many defeats but we must not be defeated." - Maya Angelou
<!-- INSPIRATIONAL_QUOTE_END -->
