# Tarea 1
## Integrantes: Ricardo Tiga Molina (Código: 3101444), Adriana Marcela Buitrago Ardila (Código: 3101438)

# Preguntas
## ¿Cuál es el problema a tratar? 
Se requiere dar a los productores de panela una herramienta que puedan utilizar para visualizar de una manera mas específica los datos inherentes a la producción de panela en los 14 departamentos productores.

[Mapa de Rendimiento QGIS](https://github.com/adrianambuitragoa/Cartografia_Web_Ricardo_Adriana/blob/master/Rendimiento_Colombia.pdf) y 
[Mapa de Producción QGIS](https://github.com/adrianambuitragoa/Cartografia_Web_Ricardo_Adriana/blob/master/Rendimiento_Colombia2.pdf)


## Por qué un mapa ayuda a resolverlo?
Un mapa es un elemento que muestra de manera gráfica la información y mas facil para una persona poder interpretarla, a diferencia de una tabla o un fichero de datos.

## Descripción del mapa temático (Variable seleccionada, utilidad)
El mapa desarrollado muestra la variable de Rendimiento en la elaboracion de la panela en los 14 departamentos productores del pais, esta se representa en Toneladas por hectarea, es útil para representar el rendimiento en la elaboracion de caña panelera en este caso, en el territorio nacional.

## Descripción de los métodos de clasificación seleccionados. Cual es mejor para la variable seleccionada? Por qué?
- Para el mapa 1, se utiliza como método de clasificación Cortes Naturales o (Jenks), se utilizan 5 con el fin de representar de una mejor manera los datos, es una aproximacion al rango de la muestra de los datos, se deben poner en rangos ya que es una mejor manera de analizar la información.

- Para el mapa 2, se utiliza el método de clasificación Quantil, con el fin de realizar una comparación con el anterior, se puede  ver que el primero tiene una mejor representación de los datos, ya que toma cinco rangos.

## Listado de fuentes de datos seleccionadas (proveedor, enlace para descarga, descripción, procesamiento realizados
Los datos son recolectados en campo por los asistentes técnicos en cada uno de los departamentos por FEDEPANELA.

El procesamiento de los mismos se lleva a cabo mediante una hoja de calculo sencilla en la cual se tienen las variables siguientes:
- Produccion de  panela por departamento(Toneladas)
- Area Cosechada (Hectareas), esta se refiere al area cosechada por departamento de caña para la produccion panelera.

Con las variables antes mecionadas se calcula el rendimiento en la producción, el cual esta dado por la siguiente formula: 

`R(Rendimiento, Ton/Ha)= Produccion(Toneladas)/Area Cosechada(Hectarea)`


## Descripción breve del procedimiento utilizado (plugins, extensiones, procesos, transformaciones de datos, etc)
Los datos se asocian a cada uno de los poligonos por departamento mediante un "join" a la tabla de excel de los datos de rendimiento y se elaboran los mapas, los datos se representan en cantidades usando colores para mostrar categorización en los valores.

## Ventajas / desventajas / dificultades / diferencias encontradas al Utilizar QGIS y Arcgis para el desarrollo del ejercicio 

- Ventajas: 
Gracias a las funcionalidades que presenta el software ArcGis o QGis de crear, compartir y utilizar mapas inteligentes, por medio de las cuales podemos llegar a compilar información geográfica y de esta manera crear y administrar bases de datos geográficas, esto se realiza encaminado a poder resolver problemas con un análisis espacial. Además el software es una herramienta muy útil para la  creación de aplicaciones basadas en mapas ya sean en escritorio o en entornos web y de esta manera poder llegar a usuarios finales para establecer un conocimiento y poder compartir  información mediante la geografía y su adecuada  visualización.

- Desventajas: El software Arcgis para el caso del ejercicio no tiene desventajas, ya que proporciona todas las herramientas para tratar los datos.

Para el desarrollo del ejercicio se utilizó arcgis y se exportó a formato pdf, se tomo la opcion de utilizar arcgis, por la facilidad para exportar a pdf.

- Dificultades: Al momento de realizar el ejercicio, ninguna, ya que se maneja cierta experticia en el manejo y elaboración de mapas, pero una persona que no tiene la experiencia en el tema no las puede manejar de manera fácil o se demoraria al momento de la generación de los mapas.
