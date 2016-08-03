# docker-mariadb-debian
Mariadb Debian Docker File

# Usage
```
$ docker run --name some-mariadb -v <docker_volume_name>:/var/lib/mysql -v <docker_volume_name>:/var/log/mysql  -v <docker_volume_name>:/var/backups/mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d uretgec/mariadb-debian:latest
```

# Many many Thanks
https://github.com/docker-library/mariadb

# Performance and Tuning Link
- http://www.tecmint.com/mysql-mariadb-performance-tuning-and-optimization
