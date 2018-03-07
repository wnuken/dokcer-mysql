# MySQL

## 1. Inicar el servicio

	sudo docker-compose up

## 2. Conectar a la base de datos:

Hosts: localhost (o IP) Port: 3306

_Ingresar a mysql desde consola_

	sudo docker exec -it mysqlservice mysql -u root -p

## 3. Dar permisos a usuario

_Dar permisos al usuario_

	GRANT ALL ON *.* TO 'developer'@'%' WITH GRANT OPTION; 
	exit;