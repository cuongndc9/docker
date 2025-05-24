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
Be a lifelong learner, not a know-it-all.
👀,
<!-- INSPIRATIONAL_QUOTE_END -->
