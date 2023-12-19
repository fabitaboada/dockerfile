Para crear una imagen personalizada de Alpine, tenemos que crear un Dockerfile. 
Una vez tenemos el archivo Dockerfile, tenemos que crear la imagen.  
Para ello emplearemos el comando:   
docker build -t fabitaboada/tarea_dockerfile:personalizada .  
 
Para subir la imagen a nuestro repositorio de Docker Hub usaremos los siguientes comandos:  
docker image tag fabitaboada/tarea_dockerfile fabitaboada/tarea_dockerfile:personalizada  
docker push fabitaboada/tarea_dockerfile:personalizada 
Para ejecutar la imagen usaremos el comando:  
docker run -it fabitaboada/tarea_dockerfile:personalizada    
Podemos comprobar que se ejecuta el navegador al lanzar el contenedor.  
Enlace al repositorio de Docker Hub:   
http://hub.docker.com/repository/docker/fabitaboada/tarea_dockerfile/general