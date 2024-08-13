## RUN Docker container
```sh
sudo docker run -p 3307:3306 --rm -d --name mysql_container --env-file=./.env mysql
```