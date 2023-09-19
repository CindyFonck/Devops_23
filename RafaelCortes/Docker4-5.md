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