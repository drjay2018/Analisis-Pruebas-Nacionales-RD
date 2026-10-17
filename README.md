<p align="center"><img src="assets/banner.svg" alt="Pruebas Nacionales de República Dominicana" width="100%"></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=geopandas&logoColor=white" alt="GeoPandas">
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" alt="Plotly">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
</p>

<p align="center">
  Parte del portafolio de <a href="https://github.com/drjay2018"><b>Jasser R. Moreno</b></a> · Análisis de Datos y Business Intelligence ·
  <a href="https://www.linkedin.com/in/jasser-moreno-medina">LinkedIn</a>
</p>

## La pregunta

¿Cómo rinden los estudiantes dominicanos en las Pruebas Nacionales, y dónde están los centros con mejores y peores resultados? Este análisis exploratorio cruza las calificaciones con el catálogo de centros educativos y con los límites geográficos del país para responderlo por materia, nivel o modalidad, género, provincia y centro.

## Qué incluye el análisis

| Sección del notebook | Qué responde |
|---|---|
| Análisis descriptivo | Calificación promedio por estudiante (Español, Matemáticas, Sociales y Naturales) y evolución de promovidos y aplazados por período |
| Rendimiento por materia y nivel/modalidad | En qué materias y modalidades se concentran los mejores y peores promedios |
| Centros de alto y bajo rendimiento | Identificación de centros por encima y por debajo del promedio |
| Análisis de género | Diferencias de rendimiento entre grupos |
| Análisis de correlación | Relación entre el desempeño en las distintas materias |
| Análisis geoespacial | Mapas interactivos por provincia y sector con los datos de rendimiento |

## Fuentes de datos

| Dato | Detalle |
|---|---|
| Estadísticas de Pruebas Nacionales 2016-2020 | Archivo Excel con calificaciones, promovidos y aplazados por centro |
| Centros educativos de República Dominicana 2021 | Portal de datos abiertos [datos.gob.do](https://datos.gob.do/dataset/centros-educativos-de-republica-dominicana) |
| Coordenadas de provincias | Tabla de apoyo para ubicar los centros |
| Shapefiles del Censo 2010 | Límites de provincia, municipio, sector y barrio/paraje |

## Stack

`pandas` · `numpy` · `matplotlib` · `seaborn` · `plotly` · `geopandas` · `fiona` · `folium` · `sweetviz` · `pandas-profiling`

## Cómo ejecutarlo

1. Abre `analisis-pruebas-nacionales-rd.ipynb` en Jupyter o en Kaggle.
2. Carga los datasets de la tabla anterior.
3. Ejecuta las celdas en orden. Las instalaciones de `sweetviz`, `pandas-profiling` e `ipywidgets` están en la primera celda.

> Las rutas de los archivos están configuradas para el entorno de Kaggle (`/kaggle/input/...`). Para correrlo en local, descarga los datasets y ajusta esas rutas.

## Mejoras previstas

- Parametrizar las rutas de entrada en una sola celda de configuración.
- Separar la extracción y la limpieza en un script reutilizable.
- Publicar los mapas como HTML independiente.

<p align="center"><sub>Datos públicos del Estado dominicano. Proyecto de análisis exploratorio con fines educativos y de portafolio.</sub></p>
