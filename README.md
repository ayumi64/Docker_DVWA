# Docker_DVWA

Build

在Dockerfile目录Run： docker build –t imagename:tag



Pull image 

docker pull sonic64/dvwa



Start with random mysql password 

docker run -d -p 80:80 sonic64/dvwa



start Run 

sudo docker run -d -p 80:80 -p 3306:3306 -e MYSQL_PASS="Chang3ME!" sonic64/dvwa




Main image ：tutum/lamp 

https://registry.hub.docker.com/u/tutum/lamp/




About DVWA 

http://www.dvwa.co.uk/

Test
http://localhost/setup.php
