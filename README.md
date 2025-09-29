📊 Análisis de Marketing Digital con Python

Archivo de análisis: datos_de_marketing.ipynb

Este proyecto analiza un conjunto de datos real de campañas de marketing digital (conversiones, clics, costes e impresiones) para evaluar su rendimiento y extraer insights accionables.

🎯 Objetivos

Analizar la efectividad de las campañas digitales.

Calcular KPIs clave: conversiones, ratio de conversión, clics y costes.

Visualizar los resultados mediante gráficos claros y reproducibles.

📂 Dataset

Formato: Excel (.xlsx)

Registros: 2.120 campañas

Columnas: grupo de anuncios, audiencia (edad, país, dispositivo, género), tipo y nombre de campaña, conversiones, clics, costes, impresiones.

⚙️ Metodología

Exploración inicial de los datos (head(), info(), describe()).

Cálculo de KPIs:

Total de conversiones

Ratio de conversión (conversiones / clics)

Coste total

Clics totales

Creación de funciones en Python para automatizar gráficos.

Generación de imágenes .png listas para portfolio/GitHub.

📈 Gráficos generados
🔹 Total conversiones por campaña

🔹 Ratio de conversión por campaña

🔹 Coste total por campaña

🔹 Clics totales por campaña

🚀 Cómo ejecutar

1️⃣ Instalar librerías necesarias:

pip install pandas matplotlib openpyxl


2️⃣ Ejecutar el notebook o script:

jupyter notebook datos_de_marketing.ipynb



Todos los gráficos se generarán automáticamente en la raíz del repositorio como archivos .png.

🔍 Conclusiones

Algunas campañas con alto presupuesto presentan bajo ratio de conversión → oportunidades de optimización.

Comparar coste y clics permite identificar la rentabilidad de cada campaña.

Próximos pasos: segmentar análisis por audiencia y dispositivo para mejorar la eficiencia.

🛠️ Tecnologías

Python (Pandas, Matplotlib)

Jupyter Notebook / Google Colab
