# MySQL

1. Conetar a la base de datos:
Hosts: localhost (or IP)
Port: 3306

2. Dar permisos a usuario

	* Ingresar a mysql

<addr> sudo docker exec -it mysqlservice mysql -u root -p

	* Dar permisos al usuario

<addr> GRANT ALL ON *.* TO 'developer'@'%' WITH GRANT OPTION;
<addr> exit;