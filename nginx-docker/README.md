# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
> "Life is what happens to you while you're busy making other plans." - John Lennon
<!-- INSPIRATIONAL_QUOTE_END -->
