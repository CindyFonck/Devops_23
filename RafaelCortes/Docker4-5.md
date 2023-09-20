# Paso 4

Para compartir imágenes de Docker, se debe crear un repositorio desde Dockerhub 

Se inicia sesión y seguido a esto se crea un repositorio como se muestra en la imagen

<p align="center"><img src="../assets/img/paso1.PNG" alt="imagen1" width="400"/></p>

Desde la terminal de docker se inicia sesión de dockerhub para poder conectar el repositorio

<p align="center"><img src="../assets/img/paso2.PNG" alt="imagen2" width="400"/></p>

Se usa docker tag para darle un nombre a la imagen

<p align="center"><img src="../assets/img/paso3.PNG" alt="imagen3" width="400"/></p>

En esta parte se monta la imagen del repositorio en Docker

<p align="center"><img src="../assets/img/paso4.PNG" alt="imagen4" width="400"/></p>

Esta parte se prueba que la imagen este correctamente montada, desde play whith docker, se ejecuta el siguiente comando para iniciar la imagen creada desde otra instancia diferente a la que estamos.

<p align="center"><img src="../assets/img/paso5.PNG" alt="imagen5" width="400"/></p>

Se especifica el puerto si no aparece para poder ver la imagem 

<p align="center"><img src="../assets/img/paso6.PNG" alt="imagen6" width="400"/></p>

De esta forma abrira la imagen creada desde otra instancia

<p align="center"><img src="../assets/img/paso7.PNG" alt="imagen7" width="400"/></p>


# Paso 5

Para esta parte se crea en el un archivo con unos datos aleatorios

<p align="center"><img src="../assets/img/paso2-1.PNG" alt="imagen2-1" width="400"/></p>

Luego validamos el id del contenedor y vemos el contenido del archivo

<p align="center"><img src="../assets/img/paso2-2.PNG" alt="imagen2-2" width="400"/></p>

Con el comando ejecutado validamos que tiene el contenedor en su raiz

<p align="center"><img src="../assets/img/paso2-3.PNG" alt="imagen2-3" width="400"/></p>

Con este comando se elimina el contenedor que se creo el cual el archivo creado se encuentra como temporal 

<p align="center"><img src="../assets/img/paso2-4.PNG" alt="imagen2-4" width="400"/></p>

Se crea un volumen llamado todo-db

<p align="center"><img src="../assets/img/paso2-5.PNG" alt="imagen2-5" width="400"/></p>

Se procede a iniciar el contenedor

<p align="center"><img src="../assets/img/paso2-6.PNG" alt="imagen2-6" width="400"/></p>

Se agregan datos, esto con el fin de validar si se conservan los datos

<p align="center"><img src="../assets/img/paso2-7.PNG" alt="imagen2-7" width="400"/></p>

Se procede a borrar el contenedor creado

<p align="center"><img src="../assets/img/paso2-8.PNG" alt="imagen2-8" width="400"/></p>

Se crea el volumen y se inicia nuevamente el contenedor, al iniciar nuevamente el puerto se evidencia que los datos si persisten

<p align="center"><img src="../assets/img/paso2-9.PNG" alt="imagen2-9" width="400"/></p>

<p align="center"><img src="../assets/img/paso2-10.PNG" alt="imagen2-10" width="400"/></p>
