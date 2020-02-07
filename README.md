# Spring Security JPA (Java Brains Tutorial)

Tutorial Code for Java Brains Spring Security JPA

YouTube: https://youtu.be/TNt3GHuayXs

### MySQL DB

Setup a MySQL DB using Docker by running:

`
docker run --restart always --name mysql8.0 --net dev-network -v /Users/gregoryweiss/code/data/mysql_data/8.0:/var/lib/mysql -p 3306:3306 -d -e MYSQL_ROOT_PASSWORD=[password] mysql:8.0
`