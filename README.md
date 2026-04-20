# Análisis de inversiones del sector asegurador argentino

Autor: Gonzalo Negrotto  
Curso: Herramientas básicas para el Análisis de Datos  
Cohorte: [Completar]

## Objetivo
El presente proyecto tiene como objetivo analizar la composición de las inversiones del sector asegurador argentino, identificando patrones de distribución, niveles de concentración y grado de diversificación entre distintos instrumentos financieros y localización geográfica (país vs exterior).

## Dataset
Se utilizó el dataset público de inversiones de la Superintendencia de Seguros de la Nación (SSN), disponible en:
https://www.datos.gob.ar/dataset/ssn-inversiones

El conjunto de datos contiene información detallada sobre inversiones realizadas por compañías aseguradoras en diferentes instrumentos financieros, tanto a nivel local como internacional.

## Metodología
Se desarrolló un proceso de análisis exploratorio de datos (EDA) utilizando Python, con las librerías pandas, matplotlib y seaborn. Se realizaron tareas de limpieza de datos, tratamiento de valores nulos, eliminación de duplicados y creación de variables agregadas para facilitar el análisis.

Posteriormente, se construyeron visualizaciones que permitieron identificar patrones relevantes, tales como la concentración de inversiones y la distribución geográfica. Finalmente, se desarrolló un dashboard interactivo en Power BI para sintetizar los principales hallazgos.

## Resultados
El análisis evidencia una fuerte concentración de inversiones en el mercado local, representando más del 99% del total. Asimismo, se observa una alta dependencia de instrumentos como títulos públicos y fondos comunes de inversión, lo que refleja un perfil conservador y una baja diversificación internacional.

## Herramientas utilizadas
- Python (pandas, matplotlib, seaborn)
- Power BI
- GitHub

## Estructura del repositorio
- /data/raw (dataset original)
- /notebooks (análisis en Python)
- /dashboard (archivo .pbix y visualizaciones)
- README.md
