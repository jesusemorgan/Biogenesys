# 🚴‍♂️ Project – Biogenesys  

💼 **Author:** Jesús E. Morgan  
📊 **Data Analyst | Python · Power BI**  
📅 **Delivery Date:** 05/08/2025  
📂 **Client:** Henry Bootcamp  

---

## 📖 Introduction  
The pharmaceutical company **BIOGENESYS** aims to identify optimal locations for the expansion of pharmaceutical laboratories, based on data analysis of COVID-19 incidence, vaccination rates, and the availability of healthcare infrastructure. The goal is to optimize the response to the pandemic and post-pandemic effects in order to improve access to vaccines.  

### Main Objectives:  
- 🧹 Improve **data quality** through cleaning and preprocessing.  
- 🔗 Build a **relational data model** aligned with business needs.  
- 🧮 Implement **DAX measures** for critical metrics.  
- 🎨 Design **intuitive and visually appealing dashboards** to support decision-making.  

---

## 🛠️ Technologies & Tools  

**Business Intelligence**  
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)   ![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)  

**Programming / Databases**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  

**DAX Language**  
![DAX](https://img.shields.io/badge/DAX-4479A1?style=for-the-badge&logo=data&logoColor=white)  

---

## 🔧 Project Development  

### 1️⃣ Data Connection and Cleaning with Python  
- Queried the **“data_latinoamerica.csv”** dataset to verify the total number of rows and columns.  
- Applied filters for the countries under analysis (Argentina, Chile, Peru, Colombia, Brazil, Mexico) and for dates starting from 01/01/2021 onwards.  
- The resulting dataset contained **3,750 rows**, making it much easier to load into a dataframe and analyze without issues.  
- During the cleaning process, we validated and removed empty rows when necessary. Regarding empty columns:  
  - Most had less than 1% missing values, which were filled using forward and backward filling.  
  - Two columns had more than 60% missing values, so they were excluded from the analysis.  

### 2️⃣ Mockup  
- Designed an **initial mockup** to guide the dashboard.  

### 3️⃣ Key DAX Measures  
- **Population, Infections, Deaths, Administered Doses.**  
- **Year-over-Year (YoY) KPIs.**  
- **Cumulative and comparative calculations.**  

### 4️⃣ Dashboard Creation  
- Implemented **navigation buttons** between pages.  

---

## 📊 Main Results  
Dynamic dashboard including:  
- Administered Doses, Infections, Deaths, and Population.  
- Slicers by Year and Country.  
- Year-over-Year (**YoY**) comparisons.  
- Organized documentation of measures and folders.  

👉 The final dashboard enables **exploration of total administered doses relative to population size** and the **infection levels**.  

---

---

## 📸 Dashboard View  

### 🔹 Main Dashboard  
![Main Dashboard](assets/dashboard_principal.png)   

---

📂 You can also explore the full project by downloading the file:  
[Download Biogenesys.pbix](assets/Biogeneys.pbix)  

📂 You can also review the ingestion, cleaning, and analysis process in Python by downloading the notebook:  
[Download Biogenesys.ipynb](https://drive.google.com/file/d/1D5r1GIZ_yqBLlUzcUwL1t5P4xvscEnQC/view?usp=sharing)  

---

## 🔮 Future Enhancements  
- Expand DAX measures for new KPIs.  
- Deepen analysis by **Country and Administered Doses**.  
- Explore integration with **real-time data**.  

---

## 💡 Personal Reflection  
This project allowed me to strengthen:  
- Accuracy and attention to detail in data cleaning, leveraging Python to handle large datasets.  
- Designing professional dashboards in Power BI.  

---

---

# 🚴‍♂️ Proyecto – Biogenesys

💼 **Autor:** Jesús E. Morgan  
📊 **Data Analyst | Python · Power BI**  
📅 **Entrega:** 05/08/2025  
📂 **Cliente:** Henry Bootcamp  

---

## 📖 Introducción  
La empresa farmacéutica BIOGENESYS busca identificar las ubicaciones óptimas para la expansión de laboratorios farmacéuticos, basándose en el análisis de datos de incidencia de COVID-19, tasas de vacunación, y la disponibilidad de infraestructuras sanitarias. La meta es optimizar la respuesta a los efectos de la pandemia y postpandemia con el fin de mejorar el acceso a las vacunas 

### Objetivos principales:  
- 🧹 Mejorar la **calidad de los datos** mediante limpieza y depuración.  
- 🔗 Construir un **modelo de datos relacional** alineado al negocio.  
- 🧮 Implementar **medidas DAX** para métricas críticas.  
- 🎨 Diseñar **dashboards visuales e intuitivos** para la toma de decisiones.  

---

## 🛠️ Tecnologías y Herramientas  

**Business Intelligence**  
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)   ![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)  

**Bases de Datos**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  

**Lenguaje DAX**  
![DAX](https://img.shields.io/badge/DAX-4479A1?style=for-the-badge&logo=data&logoColor=white)  

---

## 🔧 Desarrollo del Proyecto  

### 1️⃣ Conexión y Limpieza de Datos en Python  
- Consulté la base “data_latinoamerica.csv” para verificar el total de filas y columnas.  
- Se procedió a aplicar los filtros de los Países a trabajar (Argentina, Chile, Perú, Colombia, Brasil, México) y las fechas desde el 01/01/2021 en adelante.  
- El total de esas filas fue de 3750, lo cual fue mucho más sencillo para poder cargarlo al dataframe y analizar sin problema.
- En el proceso de limpieza aplicamos una validación de filas vacías para eliminarlas en el caso existan, y con respecto a las columnas vacías, todas las que detectamos tenían menos de 1% de celdas vacías a excepción de 2, por lo cual procedimos a rellenarlas con el último valor hacia adelante y hacia atrás; y esas 2 columnas que no rellenamos fue porque tenían más del 60% de filas vacías, y no lo vi adecuado para el análisis respectivo. 

### 2️⃣ Mockup    
- Diseño de un **mockup inicial** para guiar el dashboard.  

### 3️⃣ Medidas DAX principales  
- **N° Habitantes, Contagios, Decesos, Dosis administradas.**  
- **KPIs de variación año contra año (YoY).**    
- **Cálculos de acumulados y comparativos.**  

### 4️⃣ Creación del Tablero    
- Botones de **navegación entre páginas**.  

---

## 📊 Resultados Principales  
Tablero dinámico con:  
- Dosis administradas, Contagios, Decesos y N° Habitantes.  
- Segmentadores por Año y País.  
- Comparaciones interanuales (**YoY**).  
- Documentación organizada de medidas y carpetas.  

👉 El dashboard final facilita la **exploración del total de dosis administradas referente al N° de habitantes** y el **Nivel de contagios**.  

---

---

## 📸 Vista del Dashboard  

### 🔹 Dashboard Principal  
![Dashboard Principal](assets/dashboard_principal.png)   

---

📂 También puedes explorar el proyecto completo descargando el archivo:  
[Descargar Biogenesys.pbix](assets/Biogeneys.pbix)  

📂 También puedes explorar el proceso de ingesta, limpieza y análisis con Python, descargando el archivo:  
[Descargar Biogenesys.ipynb](https://drive.google.com/file/d/1D5r1GIZ_yqBLlUzcUwL1t5P4xvscEnQC/view?usp=sharing)

## 🔮 Líneas Futuras  
- Ampliar las medidas DAX para nuevos KPIs.  
- Profundizar en análisis por **País y dosis administradas**.  
- Explorar integración con **datos en tiempo real**.  

---

## 💡 Reflexión Personal  
Este proyecto me permitió afianzar:  
- El orden y precisión en la limpieza de datos apoyándome con Python para manejar grandes volúmenes de datos.  
- El diseño de dashboards profesionales en Power BI.  

---



