
### Setup docker
```shell
docker run --name mysql --privileged=true -e \
MYSQL_ROOT_PASSWORD="Z2Vuc29uMTgwOAo=" -e \
MYSQL_USER="food_delivery" -e \
MYSQL_PASSWORD="Z2Vuc29uMjAwMAo=" -e \
MYSQL_DATABASE="food_delivery" -p 3306:3306 bitnami/mysql:5.7

```