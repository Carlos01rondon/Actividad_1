El dataset que hace parte de esta actividad corresponde la información de las Colecciones de algunos de los espacios que conforman la Red Distrital de Bibliotecas Públicas - BibloRed.

Durante el desarrollo de esta nuestro principal problema fue la generación del archivo .csv por la cantidad de información que contiene.
Aunque al inicio no teníamos claro como se desarrollaría, lo visto en clase y con la guía del archivo de análisis del caso de Homicidios permitió establecer los parámetros que se debían ejecutar.

analysred.ipynb en este archivo, nos permite visualizar las características y la dimensión de la información contenida, los tipos de datos, identificar aquella información que quizás no es tan relevante al momento de realizar un análisis de datos.

cleanred.ipynb teniendo en cuenta lo observado en el archivo de analysred, se procedió a realizar la depuración de los datos nulos, definición del tipo de datos según la información de cada columna, ajustes en los encabezados, unificación de criterios de acuerdo al tipo de información:

Ejemplo:

Omisión de la columna Materia pues no se considero ser un punto relevante para evaluación de datos
Establecer como string los datos contenidos en columnas como Título, Autor, Ciudad, entre otros
Establecer como formato datatime los datos contenidos en la columna Fecha_de_creación
Unificación de criterios de las columnas Colección, Rubro, Tipo_de_material, entre otras con el fin que al momento de analizar los datos permitan un resultado efectivo.
