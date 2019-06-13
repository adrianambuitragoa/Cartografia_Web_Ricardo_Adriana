# Cartografia_Web_Ricardo_Adriana

# Taller 3
## Integrantes: Ricardo Tiga Molina (Código: 3101444), Adriana Marcela Buitrago Ardila (Código: 3101438)

# Preguntas

## ¿Cuál es el problema a tratar? 

Se quiere representar en un "story maps" de Arcgis los eventos sismicos que causan inundaciones en el mundo desde 1985 hasta el presente.

## ¿ Por qué una experiencia interactiva ayuda a resolverlo?


## Descripción del procesamiento realizado a los datos (ejm: transformaciones, filtros, geoprocesamiento, etc)

El siguiente mapa muestra las  Inundaciones en todo el mundo desde 1985 hasta el presente, según el Dartmouth Flood Observatory, cada punto contiene datos relevantes sobre el sismo, que ocasionó las inundaciones,  los cuales comprenden: País, Magnitud del sismo, detalle de ubicación, Causa Principal, Severidad, Grado de daño e Inundación total.
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
Se quiere en primer lugar mostrar la capa de puntos en los lugares en donde ocurrieron los sismos y posteriormente las inundaciones, esta infromación esta plasmada en la capa 1 del mapa interáctivo, en la capa dos se quiere mostrar la magnitud, la cual se agrega como atributo principal y se realiza un mapa de calor, mostrando en la leyenda el grado de magnitud, ya sea alto o bajo, representado en la paleta de colores seleccionada, En la capa tres se quiero mostrar la consecuencia de los sismos para cada una de las ubicaciones, aqui se realiza una categorizacion por el atributo de "Maincause", que señala los fenomenos tras la ocurrencia del sismo y por ultimose explica mediante un video embebido en la pagina el centro de investigación que realiza el monitorea de las variables de inundaciones en el mundo.

## Descripción de las diferentes técnicas y métodos utilizados para la visualización de datos.


## Descripción breve de las diferentes herramientas y procedimientos utilizadas para publicar el contenido en la web.


## Ventajas / desventajas / dificultades de la publicación de mapas utilizando herramientas en la nube respecto al software desktop.

## Url público de la experiencia interactiva: https://unimilitar.maps.arcgis.com/apps/MapSeries/index.html?appid=34ff5cbad9914ebc8647c66e253fd252

![Mapa Eventos Sísmicos en el mundo](https://github.com/adrianambuitragoa/Cartografia_Web_Ricardo_Adriana/blob/master/Mapa_Inundaciones_Ricardo_Adriana.png)

