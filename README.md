# Web Recetas

Práctica final de la asignatura de **Desarrollo de Aplicaciones para Internet** del Doble Grado en Ingeniería Informática y Matemáticas de la Universidad de Granada.

## Descripción

Esta página web se encarga de almacenar recetas tanto de alimentos como de bebidas. Al ingresar, es posible especificar los ingredientes requeridos y/o las instrucciones a seguir. Además, permite crear, editar y eliminar recetas para elaborar comidas y cenas originales. Asimismo, ofrece la opción de ajustar el tamaño de la fuente o activar el modo nocturno.

Por otro lado, el archivo ``/dump/cockteles/recipes.json`` contiene distintas recetas de cócteles que pueden ser añadidos a la página web.

## Ejecución

Para la ejecución de este proyecto en **Windows**, es necesario tener instalado primero ``Docker``, una herramienta que nos permitirá lanzar nuestra aplicación.

Una vez instalada, el uso de la página web es sencillo. Solo debemos ejecutar el siguiente comando en esta misma carpeta, que se encargará de construir la aplicación:

``docker-compose build``

Posteriormente, aplicamos el siguiente comando para iniciarla:

``docker-compose up``

Finalmente, solo debemos acceder al puerto correspondiente desde cualquier navegador:

``localhost:5000``

De esta manera, podremos disfrutar de la página web.
