# Taller #2 - EDA en un caso real

## Objetivo
En este taller, colaborarás en equipos de 4 a 5 miembros para seleccionar una base de datos de código abierto de Colombia o América Latina. Su objetivo es aplicar técnicas de análisis exploratorio de datos (EDA) y documentar cómo maneja los datos faltantes, los valores atípicos y las pruebas de hipótesis necesarias para su análisis. Esta tarea te ayudará a desarrollar habilidades prácticas en la evaluación de datos y la formulación de hipótesis estadísticas.

## Instrucciones
### 1. Team Building y Selección de Base de Datos (30 minutos)
Forma tu equipo: Reúna a los miembros de su equipo y discuta sus intereses en temas de datos. Asegúrese de que todos estén en la misma página con respecto a los objetivos de la tarea.

Seleccione una base de datos: elija una base de datos de código abierto que interese a su equipo. Estas son algunas plataformas recomendadas para explorar:

- Open Data Colombia: Una rica fuente de varios conjuntos de datos relacionados con los datos públicos colombianos.
- Terridata: Ofrece datos sobre desarrollo territorial y servicios públicos.
- SIVIGILA: Se centra en los datos de vigilancia de la salud pública.
- Banco Mundial - Datos Abiertos: Proporciona datos globales, incluyendo información relevante para América Latina.

Justifique su elección: Después de seleccionar una base de datos, escriba una breve justificación de su elección. Tenga en cuenta los siguientes puntos:

- ¿Cuál es la relevancia de la base de datos para su análisis?
- ¿Qué tipo de información contiene y cómo puede ser útil para su EDA?

### 2. Exploración de Bases de Datos y Tecnologías Necesarias (40 minutos)
Explorar la base de datos: Sumérgete en la base de datos seleccionada y recopila información sobre su estructura. Responda las siguientes preguntas:

- Variables disponibles: Enumere las variables presentes en el conjunto de datos e identifique el tipo de datos que contienen (por ejemplo, numéricos, categóricos).
- Total de registros: determine el número total de registros en el conjunto de datos. Analice qué tan representativa es esta muestra de la población más grande.
- Tecnologías utilizadas: Identifique las herramientas o lenguajes de programación (por ejemplo, Python, R, Excel) que utilizará para su análisis.
- Resumen estadístico inicial: Cree un resumen estadístico inicial de sus datos. Utilice visualizaciones como:

  - Diagramas de dispersión: Para mostrar relaciones entre dos variables numéricas.
  - Histogramas: Para mostrar la distribución de una sola variable numérica.
  - Tablas de frecuencias: Para resumir datos categóricos.
    
### 3. Tratamiento de Missing y Outliers (40 minutos)
Identificar valores faltantes: Examine su conjunto de datos para encontrar qué variables tienen valores faltantes. Documente la proporción de datos faltantes para cada variable.

Decidir sobre los métodos de tratamiento: Para cada variable con valores faltantes, decida un método de tratamiento. Considere las siguientes opciones:

- Eliminación: Eliminación de registros con valores faltantes.
- Imputación: Rellenar los valores que faltan utilizando métodos como:
  - Media: Promedio de los datos disponibles.
  - Mediana: Valor medio cuando se ordenan los datos.
  - Interpolación: Estimación de valores basados en puntos de datos circundantes.
- Transformación: Modificación de los datos para mejorar la calidad.
- Identificar valores atípicos: Utilice métodos como:

  - Diagramas de caja: Para identificar visualmente los valores atípicos.
  - Z-score: Para determinar qué tan lejos está un punto de datos de la media.

Decidir sobre el tratamiento de valores atípicos: Para cada valor atípico identificado, decida si:
- Eliminarlo del conjunto de datos.
- Ajústalo a un valor más aceptable.

### 4. Aplicación de Pruebas de Hipótesis (50 minutos)
Formula una hipótesis: Con base en tu base de datos, crea una hipótesis estadística. Esto debe incluir:

- Una hipótesis nula (H0): El enunciado que vas a probar.
- Una hipótesis alternativa (H1): Lo que esperas probar.

Elija una prueba estadística: Dependiendo de su hipótesis, seleccione una prueba estadística adecuada:

- Prueba t de Student: Para comparar medias entre dos grupos.
- ANOVA: Para comparar medias entre más de dos grupos.
- Prueba de Chi-cuadrado: Para examinar las relaciones entre variables categóricas.
- Pruebas no paramétricas: Si sus datos no cumplen con los supuestos de normalidad.
- Hipótesis de ejemplo: Por ejemplo, podrías decir:
"Las tasas de desnutrición infantil en las zonas rurales son significativamente más altas que en las zonas urbanas" (utilizando la prueba t de Student).
- Interpretar resultados: Después de realizar la prueba, interprete los resultados. Discuta si rechaza o no rechaza la hipótesis nula en función de sus hallazgos.

### 5. Presentación de resultados (30 minutos)
Prepara tu presentación: Crea un informe o diapositivas que incluyan las siguientes secciones:
- Descripción de la base de datos: Explique la base de datos que seleccionó y su importancia.
- Resultados EDA: Presente sus hallazgos con gráficos y un análisis detallado.
- Tratamiento de valores faltantes y valores atípicos: Resuma cómo manejó los valores faltantes y los valores atípicos.
- Hipótesis y conclusiones: Expresa tu hipótesis, las pruebas que has reunido y tus conclusiones basadas en el análisis.
