# INSTRUCCIONES DE DOCKERFILE 

## MEJORES PRÁCTICAS PARA CREAR UN DOCKERFILE



* **_ETIQUETAS_**:

- FROM: Utilizar imagenes actuales oficiales como base de sus imagenes.
inicializa una nueva etapa de construcción y establece la imagen base.

- LABEL: puede agregar etiquetas para ayudar a organizar las imagenes por proyecto, ayuda a la automatización. 

- RUN: ejecutará cualquier comando en una nueva capa encima de la imagen actual y confirmará los resultados. 

- apt-get: Instala paquetes.

- CMD: se usa para ejecutar el software contenido en su imagen, junto con cualquier argumento.

- EXPOSE:  indica los puertos en los que un contenedor escucha conexiones.

- ENV: facilita la ejecución del nuevo software, se puede utilizar ENV para actualizar la PATH variable de entorno del software que instala su contenedor.

- ADD or COPY: 

ADD: es la extracción automática del archivo local en la imagen.

COPY: admite la copia básica de archivos locales en el contenedor.

- ENTRYPOINT: configura el comando principal de la imagen.

- VOLUME: Se usa para exponer cualquier área de almacenamiento de base de datos, almacenamiento de configuración o archivos y carpetas creados por su contenedor Docker. 

- USER: se usa para cambiar a un usuario no root.

- WORKDIR: usar rutas absolutas.

- ONBUILD: se ejecuta después de que se completa la compilación actual de Dockerfile.

