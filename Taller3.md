# Cartografia_Web_Ricardo_Adriana

# Taller 3
## Integrantes: Ricardo Tiga Molina (Código: 3101444), Adriana Marcela Buitrago Ardila (Código: 3101438)

# Preguntas

## ¿Cuál es el problema a tratar? 

Se quiere representar en un "story maps" de Arcgis los eventos sísmicos que causan inundaciones en el mundo desde 1985 hasta el presente.

## ¿ Por qué una experiencia interactiva ayuda a resolverlo?


## Descripción del procesamiento realizado a los datos (ejm: transformaciones, filtros, geoprocesamiento, etc)

Los datos se obtuvieron de la pagina de Tableu en la seccion de datos abiertos y públicos, en el área de ciencias se seleccionó el tema de interes, el cual es el siguiente:

Inundaciones en todo el mundo desde 1985 hasta el presente, según el Dartmouth Flood Observatory, cada punto contiene datos relevantes sobre el sismo, que ocasionó las inundaciones,  los cuales comprenden: País, Magnitud del sismo, detalle de ubicación, Causa Principal, Severidad, Grado de daño e Inundación total.

La tabla de atributos con la descripción se detalla a continuación: 

| Atributo| Descripción|
| ----- | ---- |
Tipo de Geometria | Puntos.
Magnitude | Magnitud del sismo.
Maincause | Causa Principal de la Inundación.
Dead | Numero de muertes.
Displaced |Número de desplazamientos. 
Damage (USD) |Daño, representado en dolares.
Severity |Severidad.
Latitude |Latitud.
Longitude |Longitud.

Para la realización del "story map" en Arcgis online, se seleccionaron diversos atributos, los cuales muestran la información de una mejor manera y expone la idea de los autores de manera tal se plantea inicialmente.
Se quiere en primer lugar mostrar la capa de puntos en los lugares en donde ocurrieron los sismos y posteriormente las inundaciones, esta información está plasmada en la capa uno del mapa interáctivo, en la capa dos se quiere mostrar la magnitud, la cual se agrega como atributo principal y se realiza un mapa de calor, mostrando en la leyenda el grado de magnitud, ya sea alto o bajo, representado en la paleta de colores seleccionada, en la capa tres se quiere mostrar la consecuencia de los sismos para cada una de las ubicaciones, aquí se realiza una categorización por el atributo  "Maincause", que señala los fenomenos tras la ocurrencia del sismo y por ultimose explica mediante un video embebido en la pagina el centro de investigación que realiza el monitorea de las variables de inundaciones en el mundo.

## Descripción de las diferentes técnicas y métodos utilizados para la visualización de datos.

En la parte de visualización de datos, se hizo en "Arcgis online", en la opcion de "story maps", el cual permite combinar mapas con texto narrativo, imágenes y contenido multimedia, estos facilitan poder aprovechar la potencia de los mapas y la geografía para contar una historia.

## Descripción breve de las diferentes herramientas y procedimientos utilizadas para publicar el contenido en la web.

Primero se analizáron los datos que se descargáron de la plataforma "tableau", estos venian en formato (xlsx); luego se procede a convertir en el software "Arcgis" estos datos a puntos con la información de la latitud y longitud y poder georeferenciar los datos, paso seguido, se adicionáron las capas a la plataforma "Arcgis online" en la cual se empezó a editar la capa objetivo y a hacer los respectivos mapas categorizados como se explicó anteriormente.

## Ventajas / desventajas / dificultades de la publicación de mapas utilizando herramientas en la nube respecto al software desktop.

- Ventajas: A una perdida total de información en el computador, en la nube estan los datos cargados y listos para usarse.

- DesVentajas: 

## Url público de la experiencia interactiva: https://unimilitar.maps.arcgis.com/apps/MapSeries/index.html?appid=34ff5cbad9914ebc8647c66e253fd252

![Mapa Eventos Sísmicos en el mundo](https://github.com/adrianambuitragoa/Cartografia_Web_Ricardo_Adriana/blob/master/Mapa_Inundaciones_Ricardo_Adriana.png)

