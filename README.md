# Protocolo rejilla NTV2 para PostGIS

Protocolo que describe paso a paso como utilizar la rejilla NTV2 en PostGIS

Este protocolo sirve para utilizar la rejilla en formato NTV2 del IGN o del ICGC para transformar geometrías de ED50 a ESTRS89 utilizando correctamente la rejilla que mejor se ajusta la transformación.

Para utilizarla se tiene que llamar a la función ST_Transfom de PostGIS en cualquier sentencia sql
https://postgis.net/docs/ST_Transform.html
