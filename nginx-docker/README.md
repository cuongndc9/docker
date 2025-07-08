# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
> "A person who never made a mistake never tried anything new." - Albert Einstein
<!-- INSPIRATIONAL_QUOTE_END -->
