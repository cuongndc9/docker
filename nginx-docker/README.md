# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
The best way to predict the future is to create it.
👀,
<!-- INSPIRATIONAL_QUOTE_END -->
