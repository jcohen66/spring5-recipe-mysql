# Scripts Directory
This directory will contain SQL Migration Scripts

## Setup MySQL Container

````
docker run --name guru-mysql -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -v /home/jonathan/Dockerdata/mysql:/data/db -p 3306:3306 -d mysql
````