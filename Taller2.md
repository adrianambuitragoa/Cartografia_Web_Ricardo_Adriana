# Tarea 2
## Integrantes: Ricardo Tiga Molina (Código: 3101444), Adriana Marcela Buitrago Ardila (Código: 3101438)

# Preguntas
## ¿Cuál es el problema a tratar? 

Cuál es el record de eventos de volcanes a lo largo del tiempo 

## ¿ Por qué un mapa ayuda a resolverlo?

Mediante mapas es más fácil analizar la información georeferenciada, y para nuestro caso evidencia los lugares donde a medida que pasa la linea del tiempo se han presentado los eventos volcánicos.

## Descripción de los datos (tipos de geometrías, atributos, sistemas de referencia, urls para descarga de la información, etc)

Los datos se obtuvieron de la pagina de Tableu en la seccion de datos abiertos y públicos, en el área de ciencias se selecciono el tema de interes, el cual es el siguiente:

Erupciones volcánicas significativas:  Lista global de más de 600 erupciones volcánicas ocurridas desde el año 4360 a. C. hasta el presente, según esta base de datos de erupciones volcánicas significativas. Se entiende por erupción significativa aquella que satisface al menos uno de los siguientes criterios: causa muertes, produce daños moderados (alrededor de USD 1 millón o más), tiene un índice de explosividad volcánica (VEI) de 6 o más, genera un tsunami o está asociada con un terremoto significativo.

Tipo de datos: Conjunto de datos (xlsx)

url de descarga de la información: https://public.tableau.com/es-es/s/resources?video=AZ-cy67GJck

La tabla de atributos con la descripción se detalla a continuación: 

| Atributo| Descripción|
| ----- | ---- |
Tipo de Geometria | Puntos.
Year | Año de la explosión.
Month | Mes de la explosión.
Day | Dia de la Explosión.
Name |Nombre del Volcán. 
Location |Localización del Volcán.
Country |Pais en donde se encuentra.
Latitude |Latitud.
Longitude |Longitud.
Elevation |Elevación.
Status |Estado del Volcán.
TOTAL_DEAT |Total de muertes. 

El sistema de referencia es: WGS 84 (World Geodetic System 1984)

## Descripción del procesamiento realizado a los datos (ejm: transformaciones, filtros, geoprocesamiento, etc)

Para la realización del ejercicio se utilizó la herramienta "Carto", la cual trae incorporado diversas funcionalidades para desarrollar un mapa web, entre las que están el análisis de datos integrado y diversos "Widgets" que permiten representar de una mejor manera la información que se quiere tratar, "pop-ups", "styles" y leyenda del mapa.

Primero se analizáron los datos que se descargáron de la plataforma "tableau", estos venian en formato (xlsx); luego se procede a convertir en el software "Arcgis" estos datos a puntos con la información de la latitud y longitud y poder georeferenciar los datos, paso seguido, se adicionáron las capas a la plataforma "Carto" en la cual se empezó a editar la capa objetivo, alli se analizó lo siguiente:
Como se queria un mapa dinámico, el cual mostrara los eventos sísmicos por años, se procede a editar la capa en la categoria "styles" en la parte de "Aggregation", aqui se muestra un mapa dinamico con la columna del año de la explosión y se termina de editar en la leyenda para poder ver mejor la información y que la persona que observe el mapa lo entienda facilmente.

## Descripción de los métodos / técnicas utilizadas para la visualización.

Se deben utilizar dos métodos diferentes para representar los datos.
Cada método debe presentarse en un mapa diferente

## Descripción breve del procedimiento utilizado para publicar los mapas en la web

## Ventajas / desventajas / dificultades de la publicación de mapas utilizando herramientas en la nube respecto al software desktop.

Se presenta como ventaja la facilidad de cargar informacion y poder distribuir sus analisis sin la necesidad de generar codigo, se presenta una interfase amigable para una persona que no tiene experiencia con la creacion de mapas, ademas permite una actualizacion eficaz de los datos.

Tambien se presenta una buena salida grafica amigable con lo necesitado para mostrar al usuario final y posee una interaccion en la web aceptable con lo requerido para la publicacion.

Urls públicos de los dos mapas interactivos: 
[Mapa Interactivo Erupciones Volcánicas](https://adrianambuitragoa.carto.com/builder/185ed131-d4f3-4771-8278-b3196898261e/embed)


