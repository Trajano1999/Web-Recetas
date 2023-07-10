# Web Recetas

Práctica final de la asignatura de **Desarrollo de Aplicaciones para Internet**.

## Descripción

Esta página web se encarga de almacenar recetas tanto de comida como bebida. Una vez accedes a ella puedes indicar los ingredientes necesarios y/o las instrucciones a seguir. Puedes crear, editar y eliminar recetas para tus comidas y cenas diarias de lo más originales. Te permite además modificar el tamaño de letra o cambiar al modo nocturno si es que te dispones a cenar.

Por otro lado, el archivo `/dump/cockteles/recipes.json` contiene distintas recetas de cockteles que se pueden añadir a la página web.

## Ejecución

Para la ejecución en **Windows** de este proyecto debemos tener instalado en primer lugar `Docker`, herramienta que nos permitirá lanzar nuestra aplicación.

Una vez tengamos esto instalado, es realmente facil usar esta pagina web. Lo único que debemos de hacer es, en esta misma carpeta, el siguiente comando :

`docker-compose build`

que se encargará de construir nuestra app, para posteriormente aplicar :

`docker-compose up`

para lanzarla. Ahora, solo tenemos que entrar al puerto *5000* desde cualquier navegador de esta manera : 

`localhost:5000`

para disfrutar de la pagina web.  