# Proyecto 6: Análisis de ConnectaTel

## Objetivo del proyecto
Analizar el comportamiento de los clientes de ConnectaTel (empresa de telecomunicaciones en Latam) para identificar patrones de uso, detectar comportamientos atípicos y comprender las necesidades de diferentes segmentos, con el fin de optimizar la oferta comercial.

## Datasets utilizados
* `plans.csv`: Catálogo de planes con precios y beneficios.
* `users_latam.csv`: Información demográfica, de registro y plan contratado por cada usuario.
* `usage.csv`: Registro de actividad detallada (duración de llamadas y longitud de mensajes).

## Etapas del análisis
1. Carga y exploración de datos.
2. Identificación y corrección de problemas de calidad (valores nulos, sentinels, fechas futuras).
3. Limpieza de datos (transformación de tipos y manejo de datos tipo MAR).
4. Agrupación y resumen estadístico de uso por cliente (llamadas, minutos y mensajes).
5. Visualización de distribuciones y detección de outliers mediante histogramas y boxplots.
6. Segmentación de clientes mediante funciones personalizadas (por nivel de uso y edad).
7. Extracción de insights y recomendaciones estratégicas de negocio.

## Cómo ejecutar el notebook
1. Clona este repositorio o descarga el archivo `.ipynb`.
2. Abre el archivo en un entorno local con Jupyter Notebook/JupyterLab o súbelo a Google Colab.
3. Asegúrate de tener instaladas las librerías `pandas`, `seaborn` y `matplotlib`.
4. Ejecuta las celdas en orden descendente (Run All).
