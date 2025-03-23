Hola, en esta tarea se llevó a cabo la ejecución de un login con base de datos en spring boot y la utilización de Docker.

Primero, en la carpeta de src, accediendo a la carpeta de de main, y java, se encuentra el controlador Tarea3Application.java -  
Para ejecutar el proyecto, clona el reposiorio con: git clone https://github.com/GusValverde01/tarea3.git 
accede a la carpeta del proyecto: cd tarea3 ejecutas el proyecto con maven: mvn spring-boot:run accedes al endpoint en el navegadr con: http://localhost:8080/login. 

--Desplegar con docker--
En el directorio raiz del proyecto ejecuta: docker-compose up --build
Este comando:
Construirá la imagen de la aplicación Spring Boot a partir de tu Dockerfile.
Desplegará los contenedores de la aplicación y de MySQL.
Creará la red y los volúmenes definidos en docker-compose.yml.
Accede al login:
 http://localhost:8080/login
