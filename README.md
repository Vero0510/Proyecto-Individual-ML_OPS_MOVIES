# Proyecto-Individual MOVIES
ETL
Realice un proyecto basado en un conjunto de datos donde tenia 2 dataset en formato csv.

Obteniendo los 2 dataset se comenzo desanidando las columnas que eran necesarias para obtener mas informacion y poder hacer un join entre las tablas, luego en algunas columnas se realizaron algunas transformaciones como el tipo de dato, eliminamos valores nulos donde era necesario para el rendimiento de la API y para que los endpoints funcionen correctamente.


EDA (Analisis exploratorio de datos)
Realizamos un análisis exploratorio de datos después de completar la transformación y carga de datos (ETL). En primer lugar, obtuvimos una visión general de los años, examinamos las características de los precios, analizamos los comentarios y detectamos posibles valores duplicados.

Luego, procedimos a eliminar los valores duplicados al comparar múltiples columnas. La decisión de eliminarlos se basó en la observación de que, al hacerlo, no afectaría significativamente la integridad del dataset y calculamos la existencia de los posibles valores atipicos.

Finalmente, representamos gráficamente la distribución del análisis de........................................... a lo largo del tiempo.

Modelo de aprendizaje automático
Desarrolle una función que nos permite seleccionar un juego y obtener cinco recomendaciones de juegos similares al elegido

API
Se ha creado un entorno virtual y se han instalado todas las bibliotecas necesarias para desarrollar una API. Esta API consta de seis funciones que realizan diferentes consultas, además se creo una función donde fue entrenada con Machine Learning que nos proporciona recomendaciones de peliculas en función de la pelicula especificado en la consulta.

## Tabla de contenido
1. [Introducción](#introducción)
2. [Instalación y Requisitos](#instalación-y-requisitos)
3. [Estructura del Proyecto](#estructura-del-proyecto)
4. [Uso y Ejecución](#uso-y-ejecución)
5. [Datos y Fuentes](#datos-y-fuentes)
6. [Metodología](#metodología)
7. [Resultados y Conclusiones](#resultados-y-conclusiones)
8. [Contribución y Colaboración](#contribución-y-colaboración)
9. [Licencia](#licencia)

## Instalación y Requisitos
**Requisitos:**
- Python 3.7 o superior
- pandas
- numpy
- matplotlib
- scikit-learn

**Pasos de instalación:**
1. Clonar el repositorio: `git clone https://github.com/usuario/proyecto-ventas-ropa.git`
2. Crear un entorno virtual: `python -m venv venv`
3. Activar el entorno virtual:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Instalar las dependencias: `pip install -r requirements.txt`

## Estructura del Proyecto
- `data/`: Contiene los archivos de datos utilizados en el proyecto.
- `notebooks/`: Incluye los notebooks de Jupyter con el análisis y modelos.
- `src/`: Código fuente del proyecto, incluyendo scripts y módulos.
- `reports/`: Guarda los informes y visualizaciones generados.
- `README.md`: Archivo de documentación del proyecto.


