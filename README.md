#📊 Proceso ETL en Python – Dataset Airbnb
🎯 Objetivo

Este proyecto implementa un pipeline ETL (Extract, Transform, Load) sobre un dataset de Airbnb con el objetivo de:

Extraer datos crudos desde un archivo CSV comprimido.
Realizar limpieza y transformación de columnas (precios, fechas, tasas, valores nulos).
Generar un dataset final limpio y listo para análisis o visualización en herramientas como Power BI o Tableau.

#⚙️ Tecnologías utilizadas

Python 3
pandas para manipulación y transformación de datos
matplotlib / seaborn (para visualizaciones exploratorias)

#📂 Flujo del proceso ETL

Extract (Extracción)
Lectura del archivo listings.csv.gz (Airbnb dataset).
Transformación
Revisión de tipos de datos y valores nulos.
Limpieza de columnas numéricas: price, host_acceptance_rate, host_response_rate.
Conversión de columnas de fecha: last_scraped, host_since.
Reemplazo de códigos por información legible.
Eliminación de columnas irrelevantes.
Load (Carga)
Exportación del dataset limpio en formato .csv (listings_limpio.csv).



Listo para integrarse en dashboards o bases de datos relacionales (ej. MySQL, PostgreSQL).





