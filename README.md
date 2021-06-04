# EstadisticaII_ProyectoFinal

##Proyecto Final Estadistica II - Exploracion de Datos

##Analisis Exploratorio DataSet: 
https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks

##Planteamiento del problema:
Como entusiasta de la música, siempre quise hacer una investigación científica utilizando la informacion obtenida a travez de la API web de Spotify.

##Objetivo del estudio:
Obtener informacion a travez de diversas herramientas para crear una analisis exploratorio, analisis de la distribucion, normalidad en los datos y asi obtener informacion mas detallada y calculada de la musica.

#Resumen: La musica puede ser medida de infinidad de datos que pueden darnos informacion sobre lo que se ha escuchado y lo que se escuchara, los datos relacionados entre si que nos dan informacion del comportamiento de la musica de acuerdo a diversos factores que pueden influir en el artista, la musica en si, y la forma en como afecta a los entusiastas de la musica.

#Modelos Estadisticos Utilizados:
- Prueba shapiro
- Prueba T
- Analisis de Correlacion
- Prueba Chi cuadrado
- Prueba Anova
- Graficos: Plot, BoxPlot, Mosaico, Dispersion

Aplicaciones Utilizadas:
- R / RStudio
- Kaggle

Librerias utilizadas R Studio:
- corrplot
- stats
- dplyr
- ggplot2
- lubridate
- forecast
- tidyverse
- dplyr

Informacion Adicional:
Estructura de datos

tracks.csv
Primaria :
- id (Id de la pista generada por Spotify)
Numérico :
- acousticness  (rango de 0 a 1)
- danceability  (va de 0 a 1)
- energy  (va de 0 a 1)
- duration_ms  (número entero que suele oscilar entre 200k y 300k)
- instrumentalness  (va de 0 a 1)
- valence  (va de 0 a 1)
- popularity  (varía de 0 a 100)
- tempo (el flotador suele oscilar entre 50 y 150)
- liveness  (va de 0 a 1)
- loudness  (la flotación suele oscilar entre -60 y 0)
- speechiness  (va de 0 a 1)
Maniquí :
- mode  (0 = menor, 1 = mayor)
- explicit  (0 = sin contenido explícito, 1 = contenido explícito)
Categórico :
- key  (Todas las teclas en octava codificadas como valores que van de 0 a 11, comenzando en C como 0, C # como 1 y así sucesivamente ...)
- time_signature  (la firma de tiempo predicha, más típicamente 4)
- artists  (Lista de artistas mencionados)
- id_artists (identificaciones de los artistas mencionados)
- release_date (Fecha de lanzamiento principalmente en formato aaaa-mm-dd, sin embargo, la precisión de la fecha puede variar)
- name (nombre de la canción)
artistas.csv
- id (Id del artista)
- name (Nombre del artista)
- followers  (número total de seguidores del artista)
- popularity  (popularidad de un artista dado en función de todas sus pistas)
- genres  (géneros asociados con este artista)
