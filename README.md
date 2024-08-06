

# Equipo Gondor
### Descripcion: 
Login con un API REST hecho en java Spring Boot.

###


### Clonar repositorio
- git clone https://github.com/Zequi20/Mentoria101-Springboot.git 


### Instalación de eclipse
- Descargar [eclipse](https://eclipseide.org/)
- En la barra de menú, seleccionar Help > Eclipse Marketplace.
- En el campo de búsqueda del Marketplace, escribir “Spring Tools 4” e instalar.
- Seleccionar los componentes necesarios,
aceptar los términos de licencia y luego clic en Finish.
- Reiniciar eclipse.

### Instalación Insomnia
- Descargar [Insomnia](https://insomnia.rest/download).
- Importar archivo json de la carpeta clonada.

### Instalación mysql
- sudo apt install mysql-server
- sudo mysql_secure_installation
- nivel de password medio y colocar 'y' en los siguientes comandos.
- sudo mysql
- create database user
- CREATE USER 'dev'@'localhost' IDENTIFIED BY 'Mksgiwg#ZotA6';
- GRANT ALL PRIVILEGES ON user.* TO 'dev'@'localhost';
- FLUSH PRIVILEGES;
- exit
- mysql -u dev -p
- password: Mksgiwg#ZotA6

### Pasos Finales

- Importar el proyecto clonado
- Clic derecho sobre el nombre del proyecto y seleccionar Run As > Spring Boot App
- En caso de no ver la opcion Spring Boot App, seleccionar Run As > Run Configuration, seleccionar spring y por ultimo Run.
- Ingresar http://localhost:8080/login






