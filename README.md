# Web Comidas

Práctica final de la asignatura de **Desarrollo de Aplicaciones para Internet**.

## Descripción

Esta página web se encarga de almacenar recetas. Una vez accedes a ella puedes crear, editar y eliminar recetas para tus comidas o cenas diarias. Te permite además introducir una iamgen del resultado final de la receta. 

Además, el archivo `/dump/cockteles/recipes.json` contiene distintas recetas que se pueden añadir a la página.

## Ejecución

Para la ejecución en **Windows** de este proyecto debemos tener instalado en primer lugar `Docker`, herramienta que nos permitirá lanzar nuestra aplicación.

Una vez tengamos esto instalado, es realmente facil usar esta pagina web. Lo único que debemos de hacer es, en esta misma carpeta, el siguiente comando :

`docker-compose build`

que se encargará de construir nuestra app, para posteriormente aplicar :

`docker-compose up`

para lanzarla. Ahora, solo tenemos que entrar al puerto *5000* desde cualquier navegador de esta manera : 

`localhost:5000`

para disfrutar de la pagina web.  