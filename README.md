# automatic_tops
Automatización de videos cortos tipo tops para series, usando datos obtenidos con web scraping, entonces calificarlos y ordenarlos. Para usar la API de Youtube y encontrar los mejores videos para con ellos editar un video corto usando MoviePy

## Objetivo
El objetivo fue crear una serie de scripts que facilitarán la creación de contenido para RRSS.

El más práctico y de tendencia son los vídeos cortos. La propuesta inicial fue conseguir una base de datos de películas que permitiese calificar por género para crear un top de las mejores. Sin embargo, las etiquetas en imdb y otras plataformas no son suficientes. En cambio, hay páginas con muchos datos de etiquetas de animes, además que todos tienen un _opening_ (video músical introductorio) que puede ser la base para los vídeos y hacer su promoción.

## Tareas:

1. ✅ Conseguir información relevante usando web scraping con bs4 y selenium
2. ✅ Crear un sistema de calificación
3. ✅ Construir la base de datos de posibles videos
4. ✅ Crear un programa que busque y descargue los _openings_ usando la API de Youtube
5. ✅ Programa de edición de video para el formato vertical de un short usando moviepy
  - ✅ Identificar la parte más representativa de cada _opening_
  - ✅ Separar en tres partes y montar en un video vertical para crear clips
  - ✅ Unir los clips en el orden señalado por el top
  - ✅ Agregar introducción y título
  
  ## Conclusiones
Después de un mes de publicación se obtuvo un alcance promedio, con una proyección de 100 suscriptores para los primeros dos meses. Sin embargo, el programa no consiguió ser tan preciso o "carismático" como una persona, porque sus listados generados sí estaban correcto y fueron bien recibidos, pero ocasionalmente cometió errores.
 
