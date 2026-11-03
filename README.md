# PRÁCTICA-PYTHON
Autores: Alba y Eva
Asignatura: PYTHON  MABA – Business Analytics

1. Descripción del proyecto
2. En esta práctica se realiza un análisis de datos de una red de seis centros deportivos situados en Madrid, Barcelona y Valencia.

El objetivo es trabajar con Python para cargar, limpiar, combinar y analizar datos de actividad deportiva y meteorología, obteniendo información sobre las visitas y la ocupación de las sesiones.
2. Fuentes de datos

Se utilizan tres fuentes de información:

actividad.csv: contiene información de las sesiones deportivas, como el centro, la fecha, el tipo de actividad, el turno, las plazas y las visitas.

centros.xlsx: contiene información de los centros deportivos, como su identificador, nombre, ciudad y coordenadas.

Open-Meteo: API de la que se obtienen datos meteorológicos diarios, como temperaturas máximas y mínimas y precipitaciones, para las ciudades analizadas.

3. Archivos de entrada

Los archivos necesarios para ejecutar el proyecto se encuentran en la carpeta datos:

datos/actividad.csv

datos/centros.xlsx

4. Cómo ejecutar el proyecto en Google Colab

Abrir el archivo practica_centros.ipynb desde Google Colab.

Descargar los archivos actividad.csv y centros.xlsx del repositorio.

Crear una carpeta llamada datos en el entorno de Colab y subir ambos archivos a esa carpeta.

Comprobar que las rutas utilizadas en el notebook apuntan a los archivos de dicha carpeta.

Ejecutar las celdas en orden, desde el principio hasta el final.

El notebook consulta la API de Open-Meteo, prepara los datos, realiza las uniones y genera los análisis y gráficos.

5. Proceso de análisis

El proyecto incluye las siguientes tareas:

Lectura y preparación de los datos.

Creación de funciones para calcular y clasificar la ocupación.

Consulta de información meteorológica mediante una API.

Unión de las tablas de sesiones, centros y meteorología.

Cálculo de la ocupación y la duración de las sesiones.

Análisis estadístico con NumPy y SciPy.

Agrupaciones y resúmenes con Pandas.

Representación gráfica de los resultados.

6. Archivos de salida

Al ejecutar el notebook se genera una carpeta de resultados con los siguientes archivos:

actividad_preparada.csv

meteo_diaria.csv

resumen_centros.csv

ocupacion_por_turno.csv

visitas_diarias.csv

fuentes.json

Gráficos en formato PNG.

Todos estos archivos se incluyen en el ZIP resultados_centros.zip.
