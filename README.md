# django-postgresql-docker
 docker-compose para ejecutar un stack en producción de django conterizado

 

 # paso 1
Modificar el archivo requirements.txt con lo que se desea trabajar

# paso 2
Modificar el docker-compose.yml con las variables locales.

# paso 3
<p>
Inicia el proyecto:
</p>
docker-compose run web django-admin startproject project-new .
<p>
Cuando termine se debera bajar por completo el compose.
</p>
docker-compose down

# paso 4
Inciar por completo el ambiente:
docker-compose up -d

Si se desea ingresar al contenedor con django para ejecutar instrucciones para crear app y demas.
ejemplo:
<p>
 -- Verificar nombre o id del conteneder
</p>
docker ps 
<p>
--- Ingresar al conteendor
</p>
docker exec -it (nombre del contenedero o id) bash

# paso 5
El IDE (VSCode - spyder - PC) se le indicara que el directorio de trabajo:  /mi_directorio_pc/base



