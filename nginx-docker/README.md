# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
Be a lifelong learner, not a know-it-all.
🐶
<!-- INSPIRATIONAL_QUOTE_END -->
