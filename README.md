# Reto Técnico Comfama
Este es un proyecto que busca evaluar superficialmente las habilidades técnicas de un científico de datos.

## Descripción 
El proyecto consiste en un análisis exploratorio de datos (EDA) relacionado a los resultados obtenidos en las pruebas Saber 3°, 5° y 9° de los establecimientos educativos de Medellín para el año 2017.
Este está dividido en dos carpetas ("data" y "Analisis") las cuales contienen la data mencionada previamente, y una serie de notebooks y scripts en cuyo contenido se encuentra todo el análisis.
En la carpeta "Analisis" se encuentra:
* Script "analisis_descriptivo_multivariado" -> Se encuentran funciones que generan la matriz de varianza y covarianza, la matriz de correlación y su gráfico, el gráfico del correlograma y un gráfico de pares.
* Script "analisis_por_variable" -> Se encuentran funciones que generan tablas de frecuencias, cuartiles y un informe detallado para variables cuantitativas, donde se encuentran: Medidas de tendencia central, Medidas de variabilidad y Medidas de forma.
* Script "graficos" -> Se encuentran funciones para gráficos de tipo boxplot, histogramas y curvas de densidad.
* Notebook "exploracion" -> Se encuentra una exploración breve y superficial en la que se explica en qué consiste cada variable.
* Notebook "variables_cualitativas" -> Se encuentra el análisis de todas las variables cualitativas del dataset, en él se encontrarán tablas de frecuencias y tablas de contingencia que evidencian relaciones descriptivas entre variables.
* Notebook "variables_cuantitativas" -> Se encuentra el análisis de todas las variables cuantitativas del dataset, en él se encontrarán:
  imputación de datos por el método KNNImputer, un análisis descriptivo para cada variable, análisis de correlaciones lineales, normalización de datos a partir de transformaciones de potencias,
  pruebas de hipótesis, gráficos de normalidad, revisión de datos atípicos, reducción de dimensión por análisis de componentes principales (PCA) y clusterización.
* Notebook "relaciones_entre_var" -> Se encuentra un análisis de la data completa, donde se busca evidenciar el comportamiento y la relación entre diferentes variables categoricas con la variable "promedio", acá encontrará tablas de contingencia y un modelo de regresión logística multinomial.

# Nota
* El proyecto sienta las bases para una exploración y análisis mucho más minucioso. 
