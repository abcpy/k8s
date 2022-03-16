#

批量stop: docker stop $(docker ps -q)
docker run -d -p 80:80 nginx
docker attach c94c116dffc4
pstree -halps 1873640
docker commit
docker build -t mynginx-alpline .
docker history
docker volume ls
docker volume inspect mysql-data
docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d -v mysql-data:/var/lib/mysql mysql:5.7-debian
容器为什么能获取到ip地址
为什么宿主机可以Ping通容器的IP？
为什么容器之间的IP是互通的？
为什么容器能Ping通外网？
容器的端口转发是怎么回事？
docker network ls
iptables
docker network create -d bridge mybridge
docker network  connect bridge box3
