# 📊 Proyecto ETL en Python – Dataset Airbnb  

---

## 🎯 Objetivo  
Este proyecto implementa un **pipeline ETL (Extract, Transform, Load)** sobre un dataset de Airbnb con el objetivo de:  

✔️ Extraer datos crudos desde un archivo CSV comprimido.  
✔️ Realizar limpieza y transformación de columnas (precios, fechas, tasas, valores nulos).  
✔️ Generar un dataset final limpio y listo para análisis o visualización en herramientas como **Power BI** o **Tableau**.  

---

## ⚙️ Tecnologías y Dataset utilizadas
🔹 **Python 3**  
🔹 **pandas** → manipulación y transformación de datos  
🔹 **matplotlib / seaborn** → visualizaciones exploratorias  

Descargar el Dataset en https://insideairbnb.com/get-the-data/
---

## 📂 Flujo del proceso ETL  

### 🔹 1. Extract (Extracción)  
📥 Lectura del archivo `listings.csv.gz` (Airbnb dataset).  

### 🔹 2. Transform (Transformación)  
🧹 Revisión de tipos de datos y valores nulos.  
💲 Limpieza de columnas numéricas: `price`, `host_acceptance_rate`, `host_response_rate`.  
📅 Conversión de columnas de fecha: `last_scraped`, `host_since`.  
🔄 Reemplazo de códigos por información legible.  
🗑️ Eliminación de columnas irrelevantes.  

### 🔹 3. Load (Carga)  
💾 Exportación del dataset limpio en formato `.csv` → `listings_clean.csv`.  
📊 Listo para integrarse en dashboards o bases de datos relacionales (ej. **MySQL**, **PostgreSQL**).  

---
### IMPORTANCIA DE LIMPIAR LOS DATOS, EJEMPLO CON UN GRAFICO
ANTES:
<p align="center">
  <img src="IMAGENES DE GRAFICOS/GRAFICO(ANTES).PNG" alt="Gráfico de ejemplo" width="600"/>
</p>
DESPUES:
<p align="center">
  <img src="IMAGENES DE GRAFICOS/GRAFICO(DESPUES).PNG" alt="Gráfico de ejemplo" width="600"/>
</p>








