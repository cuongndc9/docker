# docker

Explore 🐳 Docker

<p align="center">
  <img src="https://techtalk.vn/wp-content/uploads/2018/11/1-JAJ910fg52ODIRZjHXASBQ-696x321.png" width="600"/>
</p>

## cheat sheet

### installation

- update your existing list of packages

```sh
$ sudo apt update
```

- install a few prerequisite packages which let apt use packages over HTTPS

```sh
$ sudo apt install apt-transport-https ca-certificates curl software-properties-common
```

- add the GPG key for the official Docker repository to your system

```sh
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

- add the Docker repository to APT sources

```sh
$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
```

- update the package database with the Docker packages from the newly added repo

```sh
sudo apt update
```

- make sure you are about to install from the Docker repo instead of the default Ubuntu repo

```sh
$ apt-cache policy docker-ce
```

- install Docker

```sh
$ sudo apt install docker-ce
```

- docker should now be installed, the daemon started, and the process enabled to start on boot. Check that it’s running

```sh
$ sudo systemctl status docker
```

**(Optional)** executing the Docker Command Without Sudo: [Post-installation steps for Linux](https://docs.docker.com/install/linux/linux-postinstall/)

```sh
$ sudo usermod -aG docker ${USER}
# log out and log back in so that your group membership is re-evaluated
```

**[install Docker Compose](https://docs.docker.com/compose/install/)**

### container

- [Working with Containers](https://www.tutorialspoint.com/docker/docker_working_with_containers.htm)

### Docker file

- RUN : Để thực thi một câu lệnh nào đó trong quá trình build images.
- CMD : Để thực thi một câu lệnh trong quá trình bật container.
Mỗi Dockerfile chỉ có một câu lệnh CMD, nếu như có nhiều hơn một câu lệnh CMD thì chỉ có câu lệnh CMD cuối cùng được sử dụng.

Một câu hỏi đặt ra là nếu tôi muốn khởi động nhiều ứng dụng khi start container thì sao, lúc đó hay nghĩ tới ENTRYPOINT

- ENTRYPOINT: Để thực thi một số câu lệnh trong quá trình start container, những câu lệnh này sẽ được viết trong file .sh.


## documents

- [docker from tutorialspoint.com](https://www.tutorialspoint.com/docker/index.htm)
- [Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
- [Dockerfile Best Practices](http://crosbymichael.com/dockerfile-best-practices.html)
- [Docker CLI cheatsheet](https://devhints.io/docker)
- [Docker Cheat Sheet](./docker-cheat-sheet.pdf)
- [docker-cheat-sheet](https://github.com/wsargent/docker-cheat-sheet)
- [How To Install and Use Docker on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04)
- [Docker là gì ? Kiến thức cơ bản về Docker](https://medium.com/@phamducquan/docker-l%C3%A0-g%C3%AC-ki%E1%BA%BFn-th%E1%BB%A9c-c%C6%A1-b%E1%BA%A3n-v%E1%BB%81-docker-13c6efc4aefe)
- [Docker compose là gì ? Kiến thức về Docker ( Phần 2)](https://medium.com/@phamducquan/docker-compose-l%C3%A0-g%C3%AC-ki%E1%BA%BFn-th%E1%BB%A9c-v%E1%BB%81-docker-ph%E1%BA%A7n-2-3eb546e6c846)
- [Docker Networking — Kiến thức về Docker ( Phần 3)](https://medium.com/@phamducquan/docker-networking-ki%E1%BA%BFn-th%E1%BB%A9c-v%E1%BB%81-docker-ph%E1%BA%A7n-3-94dd36138fdb)
- [Docker Swarm — Kiến thức về Docker (Phần 4)](https://medium.com/@phamducquan/docker-swarm-ki%E1%BA%BFn-th%E1%BB%A9c-v%E1%BB%81-docker-ph%E1%BA%A7n-4-e698e99b92f8)

😋 Awesome

<!-- INSPIRATIONAL_QUOTE_START -->
Discomfort is the currency of your dreams.
👻
<!-- INSPIRATIONAL_QUOTE_END -->
