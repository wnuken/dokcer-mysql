# MySQL

1. Conetar a la base de datos:
Hosts: localhost (or IP)
Port: 3306

2. Dar permisos a usuario

	* Ingresar a mysql

sudo docker exec -it mysqlservice mysql -u root -p <addr>

	* Dar permisos al usuario

GRANT ALL ON *.* TO 'developer'@'%' WITH GRANT OPTION; <addr> 
exit; <addr> 