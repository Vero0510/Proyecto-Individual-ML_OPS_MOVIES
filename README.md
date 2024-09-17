# Proyecto-Individual MOVIES

 ## Indice
1. [Extraccion, Transformacion, Load](#ETL-(Extraccion,-Transformacion,-Load))
2. [EDA (Analisis exploratorio de datos)](#EDA-(Analisis-exploratorio-de-datos))
3. [Modelo de aprendizaje automático)](#Modelo-de-aprendizaje-automatico)
4.  [Aplicacion FastAPI](##Aplicacion-FastAPI)
5. [Instalación y Requisitos](#Instalación-y-Requisitos)

## ETL (Extraccion, Transformacion, Load)
Realice un proyecto basado en un conjunto de datos donde tenia 2 dataset en formato csv.

Obteniendo los 2 dataset se comenzo desanidando las columnas que eran necesarias para obtener mas informacion y poder hacer un join entre las tablas, luego en algunas columnas se realizaron algunas transformaciones como el tipo de dato, eliminamos valores nulos donde era necesario para el rendimiento de la API y para que los endpoints funcionen correctamente.


## EDA (Analisis exploratorio de datos)

Realizamos un análisis exploratorio de datos después de completar la transformación y carga de datos (ETL). En primer lugar, obtuvimos una visión general de los años, examinamos las características de los precios, analizamos los comentarios y detectamos posibles valores duplicados.

Luego, procedimos a eliminar los valores duplicados al comparar múltiples columnas. La decisión de eliminarlos se basó en la observación de que, al hacerlo, no afectaría significativamente la integridad del dataset y calculamos la existencia de los posibles valores atipicos.

Finalmente, representamos gráficamente la distribución del análisis de........................................... a lo largo del tiempo.

## Modelo de aprendizaje automático
Desarrolle una función que nos permite seleccionar una pelicula y obtener cinco recomendaciones de peliculas similares a la elegida.

## Aplicacion FastAPI
Se ha creado un entorno virtual y se han instalado todas las bibliotecas necesarias para desarrollar una API. A traves de FastAPI y Render logramos que la API conste de seis funciones que realizan diferentes consultas, además se creo una función donde fue entrenada con Machine Learning que nos proporciona recomendaciones de peliculas en función de la pelicula especificado en la consulta.

## Instalación y Requisitos

- Python 3.9 
- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn
- FastAPI
- Uvicorn




