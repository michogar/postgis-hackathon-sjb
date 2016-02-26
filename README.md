# postgis-hackathon-sjb
Postgis en una cáscara de nuez ;-)


## Curso de PostGIS 2.0 como repositorio de datos espaciales

## Objetivo
Con la idea de introducir al alumnado en las bases de datos geoespaciales se desarrolla el siguiente curso. Se prepara a los mismos al manejo de estas comenzando por las nociones más básicas de teoría de bases de datos y acabando por operaciones complejas de análisis espacial. Además se dedica parte del temario al manejo de herramientas SIG con las que poder consultar estas bases de datos.

Al finalizar el curso el alumno podrá:
	* Instalar y configurar su propia base de datos
	* Crear un modelo de datos
	* Importar y exportar datos
	* Realizar operaciones de análisis

### Temario

* Instalación y creación base de datos
	* Instalación y configuración PostgreSQL
	* Clientes: pgsql y pgadmin3
	* Creación roles y usuarios

* PostGIS, características espaciales
	* Instalación y configuración PostGIS
	* Tablas spatial_ref, geometry_columns
	* Indices espaciales
	* Funciones espaciales
	* Módulos
		* Vectorial
		* Raster
		* Topológico
	* Tipos de datos espaciales
	* Tipos de geometrías
* Simple Feature Model
	* OGC y el Simple feature model
	* WKT y WKB
	* Definición de geometrías básicas
		* Points
		* Linestrings
		* Polygons
* Relaciones espaciales
	* Operaciones y operadores espaciales
		* ST_Intersects
		* ST_Touches
		* ST_Crosses
		* ...
* Indexación espacial
	* Creación índices espaciales
	* Utilización índices espaciales
* Importación y exportación de datos
	* Importación shapes mediante shp2pgsql
	* GDAL/OGR
		* ogrinfo
		* ogr2ogr
	* Importación datos OSM a PostGIS
		* osm2pgsql
		* osmosis
	* Consulta mediante visores web y sig escritorio
* Análisis espacial 
	* Operadores espaciales
	* Superposición
	* Proximidad
	* Generalización
	* Transformación y edición de coordenadas

