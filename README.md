# GitHub actions for Fedora 5 Docker 

This is the Git repo of the Docker image for [Fedora 5 docker](https://hub.docker.com/r/yinlinchen/fcrepo4-docker/) using GitHub actions. 

## Requirements

* [Docker](https://www.docker.com/)

## Usage

### In this Docker image

  * [Tomcat 8.0.53](https://tomcat.apache.org) at [http://localhost:8080](http://localhost:8080)
    * Manager username = "fedora4", password = "fedora4"
  * [Fedora 5.0.0](https://wiki.duraspace.org/display/FF/Downloads) at [http://localhost:8080/fcrepo](http://localhost:8080/fcrepo)
    * username = "fedoraAdmin", password = "secret3"

  ps. MacOS: docker is configured to use the default machine with IP e.g. 192.168.99.100 or 127.0.0.1, the Fedora 4 URL is either [http://192.168.99.100:8080/fcrepo](http://192.168.99.100:8080/fcrepo) or [http://127.0.0.1/fcrepo](http://127.0.0.1/fcrepo). You can use "docker-machine ip" to see your docker machine IP.

  You can shell into the machine with `docker exec -i -t "CONTAINER ID" /bin/bash`

## Contributing
If you have suggestions for how loglify could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

## License
This project are released under the [MIT License](./LICENSE)
