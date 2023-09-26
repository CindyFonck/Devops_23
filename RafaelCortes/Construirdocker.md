Para empezar a construir con docker, vamos a clonar un repositorio ya existente  

 <p align="center"><img src="../assets/img/ buildoc1.PNG" alt="imagen1" width="400"/></p> 

En el dockerfile del repositorio clonado se evidencian una serie de instrucciones como se visualiza en la imagen. 

 <p align="center"><img src="../assets/img/ buildoc2.PNG" alt="imagen1" width="400"/></p> 

 Las líneas del dockerfile están indicando que se está utilizando la versión 1.20 de alpinede. 

Se crea un directorio de trabajo llamado src dentro del contenedor. 

Copia archivos al contenedor. 

Descarga los módulos Go necesarios al contenedor. Los módulos Go son la herramienta de gestión de dependencias para el lenguaje de programación Go 

Construye el cliente binario, que se utiliza para enviar mensajes a traducir   

 Crea el server binario, que escucha las solicitudes de traducción del cliente   

 Especifica un comando para ejecutar cuando se inicia el contenedor. Inicia el proceso del servidor. 

 Con el comando indica que se crea una imagen con la etiqueta buildme. 

<p align="center"><img src="../assets/img/ buildoc3.PNG" alt="imagen1" width="400"/></p> 
