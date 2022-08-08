# Docker

{% embed url="https://dockerlabs.collabnix.com/docker/cheatsheet/" %}

```
docker ps
```

```
docker ps -a
```

```
docker images
```

```
docker run --name mysqlserver -e MYSQL_ROOT_PASSWORD=my-secret-pw -p 3306:3306 -d mysql:8
```

\--name - name

\-e&#x20;

\-p port 3306 (mysql port)

```
docker exec -it mysqlserver bash
```

\-it - interactive

enter your server "mysqlserver" - name of the service
