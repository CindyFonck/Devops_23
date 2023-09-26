# DESARROLLO CON DOCKER 

## MEJORES PRÁCTICAS DE DESARROLLO CON DOCKER

En esta parte encontraremos las mejores prácticas o patrones de desarrollo con Docker. 

* **_IMAGENES PEQUEÑAS_**:

Las imágenes pequeñas son más rápidas de transferir a la red y de cargarse en la memoria al iniciar contenedores o servicios.

- Utilizar imagenes oficiales de Docker, en lugar de crear las propias imagenes desde cero. 
ejemplo: si se neesita un JDK, incluya OpenJDK.

- Utilizar compilaciones de varias etapas. Esto quiere decir usar solo las bibliotecas o dependencias, artefactos o entornos que necesite no todo lo que contiene la imagen. Del mismo modo reducir la cantidad de capas en la imagen minimizando la cantidad de comandos en el Dockerfile. se puede hacer consolidando los comandos en una sola línea de comandos y usando los mecanismos de la shell.

<p align="center"><img src="../CindyFonseca/imagenes docker/BP IMG 1.png" alt="imagen1" width="400"/></p>

- si se tienen varias imagenes que tienen caracteristicas en común, crear una propia imagen, como imagen base.

-Usar etiquetas útiles al crear imagenes, no con las etiquetas creadas automaticamente. 


* **_CONSERVAR LOS DATOS DE LA APLICACIÓN_**:

-Evitar almacenar datos de las imagenes en la capa de escritura del contenedor.

-Almacenar datos usando volumenes.

-Use montajes enlazados durante el desarrollo.

-Use secretos para datos confidenciales y configuraciones para datos no confidenciales.

* **_UTILIZAR IC/DC_**:

-Utilice Iteración y despliegue continuo para crear y etiquetar automaticamente una imagen de Docker y probarla.



## MEJORES PRÁCTICAS DE ARCHIVOS DOCKER

Crear imagenes eficientes.

Docker crea imágenes automáticamente leyendo las instrucciones de un Dockerfile.

<p align="center"><img src="../CindyFonseca/imagenes docker/BP IMG 2.png" alt="imagen1" width="400"/></p>

- crear contenedores efímeros. esto quiere decir que se pueden detener, eliminar, reconstruir y reemplzar. 

- Entender el contexto de construcción. en otras palabras entender el argumento que pasa por el comando de compilación. la ruta de un directorio, la dirección de un repositorio, el tipo de archivo.

- Canalizar Dockerfile a través de stdin. útil para realizar compilaciones únicas sin escribir un Dockerfile en el disco.

    - Cree una imagen usando un Dockerfile desde stdin, sin enviar contexto de compilación.

    - Compile desde un contexto de compilación local, utilizando un Dockerfile desde stdin.

    - Compile desde un contexto de compilación remoto, utilizando un Dockerfile desde stdin.

- Excluir con .dockerignore.

- Utilice compilaciones de varias etapas.

- No instales paquetes innecesarios.

- Aplicaciones de desacoplamiento (Limitar cada contenedor a un proceso es una buena regla general).

- Minimizar el número de capas.
Garantiza su rendimiento.

- Ordenar argumentos de varias líneas.
ordene los argumentos de varias líneas alfanuméricamente para facilitar el mantenimiento. 

-Aprovechar la caché de compilación.
Docker busca una imagen existente en su caché, en lugar de crear una imagen nueva duplicada.

## MEJORES PRÁCTICAS DE SEGURIDAD

- Elegir la imagen base correcta de una fuente confiable y mantenerla pequeña.

- Usar compilaciones de varias etapas.

- Reconstruir imágenes.

- Verifique su imagen en busca de vulnerabilidades.
