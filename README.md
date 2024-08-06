# Top 5 Ligas Europeas

## Descripción
Análisis, limpieza y respuesta a preguntas sobre un conjunto de datos de fútbol, utilizando pandas y bibliotecas relacionadas. Tableau incorporado

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Datasets](#datasets)
   - [Appearances](#appearances)
   - [Games](#games)
   - [Leagues](#leagues)
   - [Players](#players)
   - [Shots](#shots)
   - [Teams](#teams)
   - [Teamstats](#teamstats)
3. [Preguntas de Investigación](#preguntas-de-investigación)
4. [Metodología y Herramientas](#metodología-y-herramientas)
   - [Bibliotecas Usadas](#bibliotecas-usadas)
5. [Comentarios Adicionales](#comentarios-adicionales)
6. [Contribución](#contribución)
7. [Licencia](#licencia)

## Datasets
El proyecto incluye 7 datasets en formato CSV, siendo los más interesantes `games`, `shots`, `teamstats` y `appearances`.

### Appearances
Detalla las apariciones de jugadores en partidos, incluyendo estadísticas como goles, asistencias, tarjetas amarillas y rojas, y otros datos relacionados con su desempeño individual.

### Games
Información sobre partidos específicos, incluyendo IDs de equipos local y visitante, goles marcados, probabilidades de resultados y cuotas de apuestas de varias casas.

### Leagues
Tabla que mapea IDs de liga con sus nombres y notaciones correspondientes.

### Players
Lista de jugadores con sus IDs y nombres.

### Shots
Detalles de los tiros en los partidos, incluyendo ID del juego, ID del tirador y del asistente, tipo de disparo, resultado esperado de gol (xGoal), y ubicación del disparo en el campo.

### Teams
Información sobre equipos participantes, con sus IDs y nombres.

### Teamstats
Estadísticas detalladas por equipo y partido, como goles marcados, xGoals, tiros, tarjetas amarillas, rojas, y otros indicadores de desempeño.

## Preguntas de Investigación
Algunas de las preguntas formuladas durante el proyecto incluyen:

1. ¿Cómo es la distribución de faltas según equipo por posición y por temporada?
2. ¿Cuál es el porcentaje de tarjetas amarillas en cada posición del campo de fútbol?
3. ¿De dónde suele anotar el goleador de una liga en cada temporada?. Crear un gráfico de dispersión del mejor anotador de la temporada.
4. ¿Qué ciudades ganaron más torneos?. Crear un mapa de la suma de torneos ganados de cada liga por ciudad.
5. ¿En qué lugares se juegan más partidos de las 5 mejores ligas?. Crear un mapa de calor.
6. ¿Cómo es la evolución de faltas a lo largo del tiempo en distintas ligas?. Realizar un histograma con filtros de jugadores destacados en jugadas de pelota quieta (corners, penales, tiros libres y directos).
7. ¿Qué equipos de cada liga obtienen más puntos de visitante?. Crear un gráfico de barras de equipos obtienen más puntos de visitante.
8. ¿Qué equipos por temporada han generado más situaciones de gol?. Crear un gráfico de barras de equipos que han generado más situaciones de gol por temporada.

## Metodología y Herramientas
- **Python (pandas, JupyterLab)**: Para el análisis de datos y la generación de gráficos.
- **Tableau**: Creación de un dashboard con 2 gráficos de barras, 1 mapa y 1 histograma basado en ligas.

### Bibliotecas Usadas
El proyecto utiliza las siguientes bibliotecas de Python:

- `matplotlib.pyplot`: Para la creación de gráficos.
- `matplotlib.patches`: Para dibujar formas en los gráficos.
- `pandas`: Para la manipulación y análisis de datos.
- `geopandas`: Para trabajar con datos geoespaciales.
- `contextily`: Para agregar mapas base a los gráficos geoespaciales.
- `seaborn`: Para la visualización de datos.
- `numpy`: Para operaciones numéricas.
- `folium`: Para la creación de mapas interactivos.

## Dashboard en Tableau
Puedes ver el dashboard interactivo creado en Tableau a través del siguiente enlace:

[Dashboard en Tableau](https://public.tableau.com/app/profile/fernando.torrres/viz/fin_17211741220640/Dashboard4?publish=yes)
