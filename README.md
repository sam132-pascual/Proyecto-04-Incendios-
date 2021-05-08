PROYECTO 04: INCENDIOS FORESTALES
INTEGRANTES DE EQUIPO: Samuel y Joan
DESCRIPCIÓN:
Análisis de la evolución de los incendios y las hectareas quemadas durante el periodo 2000-2015, en el que hemos analizado algunos aspectos como
origen, tipologia, correlación con los incendios...
Primero Obtenemos los datos de los incendios forestales y realizamos una lipmieza y transformacion en pandas con JupiterNotebook.
Luego la creación de los subsets que exportar a las tablas de la base de datos creada en Postgresql anteriormente en el que creamos la conexión 
mediante Psycopg2.
Luego una vez que hemos creado la conexión hemos ido llenando las tablas de la base de datos con los subsets ya extraidos.
Con Postgresql usando query tools creamos las foreign keys necesarias para unir las tablas y los inner joins necesarios para extraer y luego esportar 
los csv con los que trabajamos en Tableau.
Con Tableau creamos las conexiones a partir de esos csv y trabajamos con la visualización de los datos y creando la presentación desde el propio tableau.

URL proyecto de tableau:
https://public.tableau.com/profile/joan.uruen#!/vizhome/Proyecto_Ardiente/AnlisisIncendiosEspaa?publish=yes
