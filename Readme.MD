<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

El siguiente script tiene como finalidad poder crear un ambientes de desarrollo para trabajar sobre Laravel con MariaDB

##Requisitos
Tener instalado docker

1. Crear el proyecto laravel 
2. Colocar el archivo docker-composer.yml dentro del proyecto laravel
3. Ejecutar mediante un cmd el siguiente comando : docker-compose up -d

#Laravel

Para poder acceder al proyecto laravel en el navegador debemos colocar http://localhost:9000

##MYSQL

Para poder ingresar a la base de datos se puede hacer mediante el programa [HeidiSQL](https://www.heidisql.com/download.php) con las credenciales root, la clave es vacia y la base de datos es bitnami_myapp, recordar que el host es localhost.

