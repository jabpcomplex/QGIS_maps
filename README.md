# QGIS_maps

En este repositorio encontrarás una guía de pasos para crear mapas básicos georreferenciado, usando QGIS en su versión 3.28.0

¿Qué es QGIS?

QGIS es un Sistema de Información Geográfica de software libre y de código abierto para plataformas GNU/Linux, Unix, Mac OS, Microsoft Windows y Android.​ 
La versatilidad de software QGIS es muy poderosa dado que nos brinda la oportunidad de manipular numerosos formatos y funcionalidades de datos como datos vectoriales, datos ráster y bases de datos.

Los datos vectoriales proporcionan una forma de representar entidades del mundo real dentro del entorno GIS. Una entidad vectorial tiene su forma representada usando geometría. La geometría está formada por uno o más vértices interconectados. Un vértice describe una posición en el espacio utilizando un eje X, Y y opcionalmente Z. Las geometrías que tienen vértices con un eje ``Z”” a menudo se denominan 2.5D ya que describen la altura o la profundidad en cada vértice, pero no ambas. 

Cuando la geometría de un objeto espacial consta de un solo vértice, se denomina objeto espacial de punto. Cuando la geometría consta de dos o más vértices y el primer y último vértice no son iguales, se forma un objeto espacial de polilínea (En este mapa no usaremos este tipo de dato). Cuando hay tres o más vértices, y el último vértice es igual al primero, se forma un objeto espacial poligonal cerrado.

Dicho lo anterior, lo que primero se debe hacer es abrir el QGIS y cargas los datos de puntos y poligonos del objeto espacial que representaremos, en nuestro caso utilizaremos el connjunto de datos que contiene información geoespacial sobre epicentros en la ciudad de México desde el año 1900 y los datos vectoriales poligonales de alcaldías de la misma ciudad.


## **Sismos registrados en la ciudad de México y sus alrededores desde el año 1900**


[![Web|100](./sismo_img.png)](https://github.com/jabpcomplex/QGIS_maps)


## Referencias

1. http://www2.ssn.unam.mx:8080/catalogo/

2. https://docs.qgis.org/3.28/es/docs/gentle_gis_introduction/vector_data.html

3. https://datos.cdmx.gob.mx/dataset/sismos-registrados-cdmx
