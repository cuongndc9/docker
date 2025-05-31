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
![Image](https://github.com/user-attachments/assets/9d3847b4-d01e-4e62-b18e-12706b955cf3)
🇻🇳
<!-- INSPIRATIONAL_QUOTE_END -->
