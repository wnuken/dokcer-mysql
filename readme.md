# MySQL

##1. Conetar a la base de datos:

Hosts: localhost (or IP)

Port: 3306

##2. Dar permisos a usuario

_Ingresar a mysql_

	* sudo docker exec -it mysqlservice mysql -u root -p <addr>

_Dar permisos al usuario_

	GRANT ALL ON *.* TO 'developer'@'%' WITH GRANT OPTION; <addr> 
exit; <addr> 