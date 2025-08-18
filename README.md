# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto consiste en analizar los datos de clientes de **Telecom X** con el fin de comprender los factores que influyen en la **cancelación de servicios (churn)**.  

El análisis se desarrolló en **Google Colab** utilizando Python y sus principales librerías para procesamiento y visualización de datos.  

---

## 📌 Descripción del proyecto

Las empresas de telecomunicaciones suelen enfrentar una **alta tasa de cancelaciones**, lo que impacta directamente en sus ingresos y crecimiento.  
El objetivo de este trabajo es:

- **Procesar y limpiar los datos** de clientes.  
- **Explorar y visualizar** la información para detectar patrones.  
- **Calcular métricas de churn y retención**.  
- **Generar insights iniciales** que servirán de base para futuros modelos predictivos de churn.  

---

## 📂 Contenido

- `TelecomX_LATAM.ipynb`: Notebook principal con el análisis paso a paso.  
- `TelecomX_Data.json`: Dataset original en formato JSON.  
- `TelecomX_Data_Limpio.csv`: Dataset limpio, listo para reutilizar.  
- `outputs/`: Carpeta con gráficos y reportes generados automáticamente.  

---

## 🛠️ Herramientas utilizadas

- **Python 3**  
- **Pandas** y **NumPy** (manejo de datos)  
- **Matplotlib** y **Seaborn** (visualizaciones)  
- **Scikit-learn** (para análisis básico y futuros modelos)  
- **Google Colab**  

---

## 📈 Flujo de trabajo

1. **Extracción**:  
   Carga de los datos desde un archivo JSON.  

2. **Transformación**:  
   - Limpieza de datos (nulos, duplicados, formatos).  
   - Creación de nuevas variables (`churn`, `tenure_days`, `arpu`).  

3. **Análisis Exploratorio (EDA)**:  
   - Distribución de clientes activos vs cancelados.  
   - Churn por plan, edad, región y deuda.  
   - Correlaciones entre variables numéricas.  

4. **Resultados**:  
   Identificación de los segmentos con mayor riesgo de cancelación y factores que influyen en la evasión de clientes.  

📍 Chile – 2025

