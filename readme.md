# **Proyecto: Análisis de la Calidad del Agua**


 **Introducción**

La calidad del agua es un factor determinante para la salud pública, el desarrollo agrícola y el equilibrio ambiental de cualquier comunidad. En los últimos años, se han reportado diversos problemas de salud en la población local, así como impactos negativos en la producción agrícola debido a la presencia de contaminantes en el agua utilizada para el consumo humano y el riego. A estos problemas se suman condiciones climáticas adversas, como la escasez de lluvias, que han agravado aún más la disponibilidad y el estado del recurso hídrico.

 **Problema**

El deterioro de la calidad del agua en el área de estudio ha generado preocupación tanto en autoridades sanitarias como en sectores productivos. Se han identificado síntomas de contaminación que podrían estar relacionados con la presencia de metales pesados y otros parámetros alterados, como la salinidad, el oxígeno disuelto, el pH y la temperatura. La falta de datos sistemáticos y análisis técnicos ha dificultado la toma de decisiones informadas para mitigar esta problemática.

**Objetivo**

El objetivo principal de este proyecto es analizar la evolución de los parámetros físicos y químicos del agua en los últimos años utilizando un conjunto de datos ambientales recogido en la región. Se busca identificar tendencias, anomalías y relaciones significativas entre las variables que permitan entender el impacto del entorno en la calidad del agua y sus posibles consecuencias sobre la salud y la actividad agrícola.

**Metodología**

Para llevar a cabo este análisis, se utilizará un enfoque cuantitativo basado en técnicas de ciencia de datos con Python. Se emplearán herramientas como pandas, seaborn, matplotlib y scikit-learn para la limpieza de datos, visualización, selección de características y modelado predictivo. Entre las variables analizadas se encuentran: oxígeno disuelto, salinidad, pH, temperatura del agua y del aire, y profundidad. Además, se aplicarán modelos de regresión y análisis de correlación para explorar cómo han cambiado estos parámetros en el tiempo y si están asociados con indicadores de contaminación o estrés ambiental.

**Principales hallazgos esperados**
Se espera identificar si la calidad del agua ha empeorado en los últimos años y cuáles son los factores más influyentes. En particular, se buscará verificar si hay un aumento en la temperatura del agua (posiblemente vinculado al cambio climático), una reducción del oxígeno disuelto (indicador clave de vida acuática) y evidencia de concentraciones elevadas de metales pesados o salinidad que puedan afectar cultivos y salud. Estos hallazgos servirán como base para futuras intervenciones y monitoreos ambientales más precisos.



# Propuestas de mejora basadas en los datos analizados

A partir del análisis estadístico y del modelo predictivo aplicado, se identificaron variables clave que influyen significativamente en la temperatura del agua, un parámetro fundamental para evaluar la calidad del recurso hídrico. En función de estos hallazgos, se proponen las siguientes recomendaciones de mejora para las autoridades competentes:

1. Monitoreo sistemático de temperatura del aire y del agua

Dado que la temperatura del aire fue la variable más influyente, se recomienda instalar estaciones meteorológicas o sensores automáticos para medir temperatura ambiental y del agua en tiempo real. Esto permitirá detectar anomalías rápidamente.

2.Control y seguimiento del pH y salinidad

Se detectó que el pH tiene una relación importante con la temperatura del agua, y la salinidad también tiene peso moderado. Se sugiere implementar controles regulares del pH y la salinidad, sobre todo en épocas de altas temperaturas o sequías, para prevenir deterioros de la calidad del agua.

3.Plan de remediación o tratamiento del agua

En zonas donde los valores de pH o salinidad estén fuera del rango aceptable para el consumo o riego, implementar tecnologías de corrección (oxigenación, neutralización, desalinización u otras) podría mitigar los impactos sobre la salud pública y los cultivos.

4.Protección de áreas vegetadas ribereñas

La vegetación en las cercanías de los cuerpos de agua actúa como regulador térmico y contribuye a mantener la calidad del agua. Se recomienda proteger o reforestar las zonas de ribera o cuencas para evitar el aumento sostenido de temperatura y pérdida de oxígeno disuelto.

5. Fortalecimiento de los sistemas de información hídrica

La falta de datos fue una limitante inicial. Se propone generar una base de datos centralizada con indicadores de calidad del agua que incluya monitoreos frecuentes y variables fisicoquímicas clave, integrando datos de distintas instituciones y organismos.

6.Implementación de modelos predictivos en la gestión pública

Incorporar modelos como Random Forest en los sistemas de alerta temprana puede ayudar a anticipar situaciones de riesgo hídrico o contaminación, permitiendo una respuesta más eficiente por parte de los organismos responsables.

* Fuente de datos:
https://www.kaggle.com/datasets/sahirmaharajj/water-quality-data