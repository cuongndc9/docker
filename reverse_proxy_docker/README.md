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
> "The only impossible journey is the one you never begin." - Tony Robbins
<!-- INSPIRATIONAL_QUOTE_END -->
