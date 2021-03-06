# 01 - Laboratorio Docker

Para este laboratorio practico, lea atentamente las instrucciones.

Cree un fork público a partir de este repositorio.

Dentro del repositorio generado a partir de tu fork, cree una rama para cada una de las preguntas del laboratorio, en ellas cree una carpeta de nombre “PREGUNTA_N#” donde (#) corresponde al numero correlativo de la pregunta, donde desarrollará el ejercicio.

Una vez finalice el desarrollo en la rama correspondiente, cree y cierre un merge request, fucionando los cambios hacia la rama main.
Para cada pregunta, cree un README.md en su carpeta correspondiente con el paso a paso de su solución, (Se utilizará en revisión del laboratorio).


1. Desarrolle una receta Dockerfile que permita cargar y desplegar un index.html con el texto “¡Hello Zippy!”, el servicio debe poder ser accedido desde el puerto 8080.
Adjunte el Dockerfile como archivo, comando de construcción y despliegue de contenedor en el README.md correspondiente. (Elija libremente una imagen Docker que permita realizar está acción, sugerimos utilizar NGINX). 


2. Utilizando el Dockerfile anterior, elabore una forma de despliegue para actualizar el documento “index.html” sin necesidad de recrear el contenedor cada vez que este sea modificado.
Adjunte su solución en el archivo README.md correspondiente.

Consejo: Investigue el uso de volumenes compartidos.


3. Despliegue un contenedor con MySQL, luego cree un usuario y contraseña, asegúrese de que tiene conectividad desde su equipo local a la instancia de BD. Adjunte el comando para crear este contenedor.


Al término del laboratorio, realice un merge request a la rama "main". 

Envíanos tu repositorio al correo de selección, si no tuviste tiempo de finalizar todas las preguntas, no te preocupes. 


¡ Mucho éxito !



Documentos de apoyo:

Instalación Docker Ubuntu:   https://docs.docker.com/engine/install/ubuntu/ (Se recomienda utilizar sistema operativo basado en Linux)

Instalación Docker Mac: https://docs.docker.com/desktop/mac/install/ 

Instalación Docker en Windows: https://docs.docker.com/desktop/windows/install/ 

Uso de Dockerfiles:  https://docs.docker.com/engine/reference/builder/



