## cat_service

```sh
$ docker build -t cat_service .
$ docker run -d --name cat-service cat_service
```

## nginx

```sh
$ docker build -t nginx-docker .
$ docker run -d -p 8000:80 --link cat-service nginx-docker
```


<!-- INSPIRATIONAL_QUOTE_START -->
> "We may encounter many defeats but we must not be defeated." - Maya Angelou
<!-- INSPIRATIONAL_QUOTE_END -->
