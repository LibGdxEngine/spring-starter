my starter spring boot app

# Run docker file for mysql database
docker run -d -p 3306:3306 --name mysql-container -e MYSQL_ROOT_PASSWORD=ahmed1998 -e MYSQL_DATABASE=mydb -e MYSQL_USER=ahmed -e MYSQL_PASSWORD=ahmed1998 mysql:latest