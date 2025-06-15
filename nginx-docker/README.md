# nginx with Docker

## without Dockerfile
```sh
$ docker run --name nginx-docker -p 9000:80 -v "$PWD":/usr/share/nginx/html:ro -d nginx
``

<!-- INSPIRATIONAL_QUOTE_START -->
> "If you are working on something that you really care about, you don't have to be pushed. The vision pulls you." - Steve Jobs
<!-- INSPIRATIONAL_QUOTE_END -->
