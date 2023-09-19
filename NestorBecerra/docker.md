# Usar Docker Compose 


## Paso 1: Crear un directorio. 

 

 

 

## Paso 2: Crear un archivo docker-compose.yml. 

 

 

 

 

 

 

## Paso 3: Definir los servicios en docker-compose.yml 

 

 

 

Este archivo docker-compose.yml define dos servicios: app y mysql. El servicio app utiliza la imagen de node 18 como servidor  y mapea el puerto 3000 del host al puerto 3000 del contenedor. Además, se utiliza un volumen para servir archivos HTML personalizados desde la carpeta ./html en el host. 

El servicio mysql utiliza la imagen de MySQL y configura algunas variables de entorno como la contraseña de root y el nombre de la base de datos. 

 


## Paso 4: Crear la carpeta para los archivos HTML personalizados. 

 

 

 

## Paso 5: Agregar un archivo HTML personalizado. 

 

 

 

## Paso 6: Ejecutar la aplicación. 

 

 

 

 

 

 

 