## Práctica M2B - Mapa temático de gimnasios de BCN

He querido mostrar en un mapa la situación de 3 de las cadenas de gimnasios de Barcelona más conocidas. De esta manera se puede ver su distribución en la ciudad. Además encuentro muy útil este mapa para un usuario que quiera buscar gimnasios que le quedan cerca...por ejemplo, un usuario que cambia de trabajo o se muda a la ciudad y quiere saber que los gimnasios que tiene alrededor.

La práctica está hecha en leaflet y contiene lo siguiente:

- **datos reales de los gimnasios**. 
>Para ello se han consultado las webs de los gimnasios, sacando sus datos como dirección y web para plasmarlos sobre el mapa. He generado un geojson con todas esta información. Para sacar las coordenadas de todos los gimnasios a través de su dirección (geocodificación inversa) he usado un programa que nos pasó Sergio Manzanero para su práctica. Existen también otros métodos para sacar este dato (Vissir del institut cartogràfic). Además también podría haber generado este geojson a través de QGIS.

 - **control de zoom:** 
 >se pone a falso el control de zoom del mapa para poder cambiar los literales que aparecen cuando paso el ratón por encima del símbolo + y -

- **se añade un cambio de color en el marker**, en función de la cadena de gimnasios que es:
>- lila: Anytime fitness
>- naranja: Duet Fit
>- azul: DIR

>**Note:** Este cambio se hace con un switch.

- se **añade en el pop-up un link** para ir a la página concreta del gimnasio y poder consultar cualquier dato que se requiera del gimnasio.

- se pueden ver **varias capas sobre el mapa**.

## Documentación

[Ver aquí]
(https://github.com/ElianaRR/practica)
