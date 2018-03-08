# MySQL

## 1. Inicar el servicio

	sudo docker-compose up

## 2. Conectar a la base de datos:

Host: localhost (o IP) Port: 3306

_Ingresar a mysql desde consola_

	sudo docker exec -it mysqlservice mysql -u root -p

## 3. Usuarios

_Crear y dar permisos al usuario_

	CREATE USER 'developer'@'%' IDENTIFIED BY 'd3v3l0p3r';
	GRANT ALL ON *.* TO 'developer'@'%' WITH GRANT OPTION;
	FLUSH PRIVILEGES;
	exit;