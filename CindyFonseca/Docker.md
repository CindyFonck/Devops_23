# DOCKER

## DESCRIPCIÓN GENERAL

Docker es una plataforma de código abierto que permite a los desarrolladores crear, implementar, ejecutar, actualizar y gestionar contenedores, que son componentes estandarizados y ejecutables que combinan el código fuente de la aplicación con las bibliotecas y dependencias del sistema operativo (SO) necesarias para ejecutar ese código en cualquier entorno.

* **_CONTENEDORES_**:

Los contenedores Docker son las instancias activas y en ejecución de las imágenes de Docker. Si bien las imágenes de Docker son archivos de solo lectura, los contenedores son contenido en vivo, efímero y ejecutable. Los usuarios pueden interactuar con ellos y los administradores pueden ajustar su configuración y condiciones mediante los comandos de Docker.
Permiten que varios componentes de la aplicación compartan los recursos de una sola instancia del sistema operativo host de la misma manera que un hipervisor permite que varias máquinas virtuales (VM) compartan la CPU, la memoria y otros recursos de un único servidor de hardware.

* **_IMAGENES_**:

Las imágenes de Docker contienen el código de origen de la aplicación ejecutable, así como todas las herramientas, bibliotecas y dependencias que el código de la aplicación necesita para ejecutarse como un contenedor. Cuando ejecuta la imagen de Docker, se convierte en una instancia (o varias instancias) del contenedor.

* **_DOCKERFILE_**:

Cada contenedor Docker comienza con un archivo de texto simple que contiene instrucciones acerca de cómo crear la imagen de contenedor Docker. DockerFile automatiza el proceso de creación de imagen de Docker. Es esencialmente una lista de instrucciones de interfaz de línea de comando (CLI).



## GUIA DOCKER

1. Clonar el repositorio: 

<p align="center"><img src="../CindyFonseca/imagenes docker/LC CLONAR REPOSITORIO.jpg" alt="imagen1" width="400"/></p>

<p align="center"><img src="../CindyFonseca/imagenes docker/img 1.png" alt="imagen1" width="400"/></p>


2. Crear un archivo vacío:

<p align="center"><img src="../CindyFonseca/imagenes docker/LC TOUCH.jpg" alt="imagen1" width="400"/></p>

<p align="center"><img src="../CindyFonseca/imagenes docker/img 4.png" alt="imagen1" width="400"/></p>

<p align="center"><img src="../CindyFonseca/imagenes docker/img 5.png" alt="imagen1" width="400"/></p>

3. Construir una imagen:

<p align="center"><img src="../CindyFonseca/imagenes docker/LC CONSTRUIR IMG.jpg" alt="imagen1" width="400"/></p>

<p align="center"><img src="../CindyFonseca/imagenes docker/img 6.png" alt="imagen1" width="400"/></p>

4.	Ejecutar la aplicación en un contenedor:

<p align="center"><img src="../CindyFonseca/imagenes docker/LC EJECUTAR LA APP.jpg" alt="imagen1" width="400"/></p>


5.	Listas los contenedores:

<p align="center"><img src="../CindyFonseca/imagenes docker/LC LISTAR LOS CONT.jpg" alt="imagen1" width="400"/></p>


6.	Actualizar una imagen:
    - Parar la ejecución del contenedor.
    - Eliminar el contenedor antiguo.

<p align="center"><img src="../CindyFonseca/imagenes docker/LC ACTUALIZAR LA IMAGEN.jpg" alt="imagen1" width="400"/></p>


7.	Parar y eliminar un contenedor:

<p align="center"><img src="../CindyFonseca/imagenes docker/LC ELIMINAR CONT .png" alt="imagen1" width="400"/></p>

8. Resultados

<p align="center"><img src="../CindyFonseca/imagenes docker/RESULTADO.png" alt="imagen1" width="400"/></p>

