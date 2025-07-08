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
> "Success is not how high you have climbed, but how you make a positive difference to the world." - Roy T. Bennett
<!-- INSPIRATIONAL_QUOTE_END -->
