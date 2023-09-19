# Usar Docker Compose 


## Paso 1: Crear un directorio. 

 

 <p align="center"><img src="../assets/img/com1.png" alt="imagen1" width="400"/></p>

 

## Paso 2: Crear un archivo docker-compose.yml. 

 

  <p align="center"><img src="../assets/img/com2.png" alt="imagen1" width="400"/></p>

 

 

 

 

## Paso 3: Definir los servicios en docker-compose.yml 

 
 <p align="center"><img src="../assets/img/com3.png" alt="imagen1" width="400"/></p>
 

 

Este archivo docker-compose.yml define dos servicios: app y mysql. El servicio app utiliza la imagen de node 18 como servidor  y mapea el puerto 3000 del host al puerto 3000 del contenedor. Además, se utiliza un volumen para servir archivos HTML personalizados desde la carpeta ./html en el host. 

El servicio mysql utiliza la imagen de MySQL y configura algunas variables de entorno como la contraseña de root y el nombre de la base de datos. 

 


## Paso 4: Crear la carpeta para los archivos HTML personalizados. 

 
 <p align="center"><img src="../assets/img/com4.png" alt="imagen1" width="400"/></p>
 

 

## Paso 5: Agregar un archivo HTML personalizado. 

 

  <p align="center"><img src="../assets/img/com5.png" alt="imagen1" width="400"/></p>

 

## Paso 6: Ejecutar la aplicación. 


 <p align="center"><img src="../assets/img/com6.png" alt="imagen1" width="400"/></p>
 

 
