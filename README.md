📊 Análisis de Marketing Digital – Python

Archivo de análisis interactivo: datos_de_marketing.ipynb
Script reproducible: analisis_marketing.py (genera gráficos automáticamente)

Este proyecto analiza un dataset real de campañas de marketing digital (conversiones, clics, costes e impresiones) para evaluar su rendimiento y extraer insights accionables.

🎯 Objetivos

Analizar la efectividad de las campañas digitales.

Calcular KPIs clave: conversiones, ratio de conversión, clics y costes.

Visualizar los resultados mediante gráficos claros y reproducibles.

📂 Dataset

Formato: Excel (.xlsx)

Registros: 2.120 campañas

Columnas principales: grupo de anuncios, audiencia (edad, país, dispositivo, género), tipo y nombre de campaña, conversiones, clics, costes, impresiones.

⚙️ Metodología

Notebook interactivo (datos_de_marketing.ipynb)

Permite explorar los datos paso a paso (head(), info(), describe())

Incluye comentarios y análisis exploratorio

Genera gráficos inline para visualización rápida

Script reproducible (analisis_marketing.py)

Calcula automáticamente los KPIs por campaña

Genera gráficos .png en la carpeta images

Ideal para reproducir resultados sin abrir el notebook

📈 KPIs calculados

Total de conversiones por campaña

Ratio de conversión = conversiones / clics

Coste total por campaña

Clics totales por campaña

📊 Gráficos generados
🔹 Total conversiones por campaña

🔹 Ratio de conversión por campaña

🔹 Coste total por campaña

🔹 Clics totales por campaña

(Los gráficos se generan automáticamente al ejecutar analisis_marketing.py.)

🚀 Cómo ejecutar

1️⃣ Instalar librerías necesarias:

pip install pandas matplotlib openpyxl


2️⃣ Ejecutar notebook:

jupyter notebook datos_de_marketing.ipynb


3️⃣ Ejecutar script reproducible:

python analisis_marketing.py

🔍 Conclusiones

Algunas campañas con alto presupuesto presentan bajo ratio de conversión → oportunidades de optimización.

Comparar coste y clics permite identificar la rentabilidad de cada campaña.

Próximos pasos: segmentar análisis por audiencia y dispositivo para mejorar eficiencia.

🛠️ Tecnologías

Python (Pandas, Matplotlib)

Jupyter Notebook / Google Colab
