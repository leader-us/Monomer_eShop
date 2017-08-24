# Monomer_eShop
单体应用，简单电商Demo，基于Spring Boot，包括分布式Session等基本功能
配置文件在 main/resource/application.yaml中，包括数据库，redis连接信息
数据库初始化用户名，密码 guest/111111
docker 方式启动reids，mysql ，即可测试运行
docker run d  -p 6379:6379 redis

docker run -d   -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=HPE_APP -e MYSQL_USER=lession -e MYSQL_PASSWORD=mypass -p 3306:3306 mysql:5.7

