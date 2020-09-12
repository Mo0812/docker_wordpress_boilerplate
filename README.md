# docker_wordpress_boilerplate

**docker_wordpress_boilerplate** represents a docker boilerplate which I use to develop wordpress themes and plugins independently of any dependencies installed on the local development environment. To make it work just run:
```
docker-compose up -d --build
```
After docker has downloaded all missing dependencies and containers you end up with a running wordpress instance accessible under `http://localhost:8000`. The used port can be changed in the `docker-compose.yml` file.

The needed Wordpress files are located in the folder `wordpress`. Changes for that files directly lead to a change of the code of the running Wordpress instance in the provided container.