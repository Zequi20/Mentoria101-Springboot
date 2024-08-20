

# Equipo Gondor
### Descripcion: 
Login con un API REST hecho en java Spring Boot.

### Pasos para instalar en Ubuntu

### Prerrequesitos
- JDK 17
- [Maven](https://www.digitalocean.com/community/tutorials/install-maven-linux-ubuntu#installing-maven-on-linux-ubuntu)
- MySQL

### Clonar repositorio
- git clone https://github.com/Zequi20/Mentoria101-Springboot.git 


### Instalación de eclipse (opcional)
- Descargar [eclipse](https://eclipseide.org/)
- En la barra de menú, seleccionar Help > Eclipse Marketplace.
- En el campo de búsqueda del Marketplace, escribir “Spring Tools 4” e instalar.
- Seleccionar los componentes necesarios,
aceptar los términos de licencia y luego clic en Finish.
- Reiniciar eclipse.
  
### Instalación mysql
```
sudo apt install mysql-server
```
```
sudo mysql_secure_installation
```

Nivel de password medio y colocar 'y' en los siguientes comandos.
```
sudo mysql
```
```
create database user;
```
```
CREATE USER 'dev'@'localhost' IDENTIFIED BY 'Mksgiwg#ZotA6';
```
```
GRANT ALL PRIVILEGES ON user.* TO 'dev'@'localhost';
```
```
FLUSH PRIVILEGES;
```
```
exit
```
```
mysql -u dev -p
```
Password:
```
Mksgiwg#ZotA6
```

### Correr el proyecto con Maven en consola
Navegar a la carpeta del proyecto clonado:
  ```
  cd Mentoria101-Springboot
  ```
  ```
  mvn clean package
  ```
  ```
  mvn spring-boot:run
  ```
  
### Correr el proyecto con Eclipse
- Importar el proyecto clonado
- Clic derecho sobre el nombre del proyecto y seleccionar Run As > Spring Boot App
- En caso de no ver la opcion Spring Boot App, seleccionar Run As > Run Configuration, seleccionar spring y por ultimo Run.

### Ingresar http://localhost:8080/login


### Al ingresar al login pueden crear una nueva cuenta si no estan registrados.
