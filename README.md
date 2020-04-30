# django-postgresql-docker
 docker-compose para ejecurtar un entorno de desarrollo con docker

 La facilidad es poder trabajar varios proyectos desde docker sin instalar localmente versiones de python o librerias.

 #paso 1
Modificar el archivo requirements.txt con lo que se desea trabajar

#paso 2
Modificar el docker-compose.yml con las variables locales.

#pase 3
Inicia el proyecto:
docker-compose run web django-admin startproject project-new .

Cuando termine se debera bajar por completo el compose.
dokcer-compose down

#paso 4
Inciar completo el ambiente:
docker-compose up -d

Si se desea ingresar al contenedor con django para ejecutar instrucciones para crear app y demas.
ejemplo:
-- Verificar nombre o id del conteneder
docker ps 

--- Ingresar al conteendor
docker exec -it (nombre del contenedero o id) bash

#paso 5
El IDE (VSCode - spyder PC) se le indicara que el directorio de trabajo:  /mi_directorio_pc/base



