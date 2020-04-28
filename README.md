# COVID-19 en España

Conjunto de datos que refleja los casos confirmados y muertes por COVID-19 en
España, a nivel provincial.

## Notas importantes

> :warning: **Fecha de fin**: a partir del 18 de abril en algunas comunidades y
> provincias no se da por separado los positivios por PCR y test rápido, con lo
> que los casos nuevos dejan de ser válidos. En caso de poder obtener datos
> fiables, se actualizaría el conjunto de datos.

> :warning: **Galicia**: 60 muertes sin contabilizar, correspondientes a las
> residencias con anterioridad al 18 de abril.

> :warning: **Aragon**: El número de muertes y casos son inferiores a los
> reales, puesto que hay algunos casos no asignados a ninguna provincia.

> :warning: **Cataluña**: El número de casos son inferiores a los reales,
> puesto que hay algunos casos no asignados a ninguna provincia.

> :warning: **Cataluña**: No se dispone de muertes por provincia.

> :warning: Pueden existir ligeras fluctuaciones en los datos de los primeros
> días en cada provincia, cuando aún no se proporcionaban los datos de forma
> sistematizada.

## Descripción

| Campo/Field   | Descripción                       | Description                   | Formato/Format    | Ejemplo/Example   |
|---------------|-----------------------------------|-------------------------------|-------------------|-------------------|
| date          | Fecha de publicación              | Publication date              | YYYY-MM-DD        | 2020-04-16        |
| id            | ID (INE) de comunidad autónoma    | Region ID (INE)               | int               | 7                 |
| region        | Nombre de la comunidad autónoma   | Region name                   | text              | Castilla y León   |
| pid           | ID (INE) de la provincia          | Province ID (INE)             | int               | 24                |
| province      | Nombre de la provincia            | Province name                 | text              | León              |
| cases acc     | Casos positivos acumulados        | Accumulated positive cases    | int               | 2119              |
| cases new     | Nuevos casos positivos            | New positive cases            | int               | 184               |
| deaths acc    | Muertes acumuladas                | Accumulated deaths            | int               | 283               |
| deaths new    | Nuevas muertes                    | New deaths                    | int               | 4                 |

## Licencia

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licencia Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Esta trabajo está bajo una <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Licencia Creative Commons Atribución 4.0 Internacional. <br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Fuentes de datos

Para la realización de este conjunto de datos se han consultado las siguientes
fuentes de información y datos:

* Andalucía: comunicados diarios publicados en la página de la [Junta de
  Andalucía](https://www.juntadeandalucia.es/organismos/saludyfamilias/actualidad.html)
* Aragón: actualizaciones diarias publicadas en la [página de comunicación del
  Gobierno de Aragón](http://www.aragonhoy.net/)
* Islas Baleares: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* Canarias: [mapa interactivo del Gobierno de
  Canarias](https://grafcan1.maps.arcgis.com/apps/opsdashboard/index.html#/156eddd4d6fa4ff1987468d1fd70efb6)
  y [gráficos publicados en
  eldiario.es](https://www.eldiario.es/canariasahora/sociedad/coronavirus-Canarias-mapas-graficos_0_1008599481.html)
* Cantabria: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* Castilla y León: [portal de datos de la Junta de Castilla y
  León](https://datosabiertos.jcyl.es/web/es/datos-abiertos-castilla-leon.html)
* Castilla-La Mancha: [notas de prensa de la Consejería de Sanidad del Gobierno
  de Castilla-La
  Mancha](https://sanidad.castillalamancha.es/ciudadanos/enfermedades-infecciosas/coronavirus/notas-prensa)
* Cataluña: [datos abiertos de la Generalitat de
  Cataluña](http://governobert.gencat.cat/ca/dades_obertes/dades-obertes-covid-19/)
* Comunidad Valenciana: [notas de prensa diarias de la página del gabinete de
  comunicación de la Generalitat
  Valenciana](https://www.gva.es/es/inicio/area_de_prensa/ap_notas_prensa?tipoContenido=26&zona=21&botonBuscar=buscar&busquedaorganismo=3.07)
* Extremadura: [noticias diarias de la Consejería de Sanidad y Servicios
  Sociales de la Junta de Extremadura](http://www.juntaex.es/con05/)
* Galicia: [notas de prensa diarias del área de sanidad de la Xunta de
  Gacilia](https://www.xunta.gal/notas-de-prensa)
* Madrid: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* Murcia: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* Navarra: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* País Vasco: [datos abiertos del Gobierno de el País
  Vasco](https://opendata.euskadi.eus/catalogo/-/evolucion-del-coronavirus-covid-19-en-euskadi/)
  y [web
  EITB](https://www.eitb.eus/es/noticias/sociedad/detalle/7110777/casos-coronavirus-euskadi-pueblo-pueblo-edades/)
* La Rioja: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* Ceuta: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
* Melilla: [dataset de casos de covid-19 por comunidad autónoma de
  Datadista](https://github.com/datadista/datasets/blob/master/COVID%2019/ccaa_covid19_casos.csv)
