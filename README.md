# Rappi-Plus-Analisis

RappiPlus es un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario.

Sin embargo, el equipo de negocio no tiene claro si el servicio está cumpliendo su objetivo.

Existen dudas clave:

¿Los usuarios realmente compran más?
¿El modelo está generando ganancias?
¿Se están perdiendo oportunidades en el proceso de compra?

## 📂 Dataset del proyecto (Exploración, Limpieza y Cálculos KPIs)
El análisis comienza con tres fuentes principales:

rappiplus_orders_raw.csv
rappiplus_catalog.csv
rappiplus_marketing_spend.csv

https://practicum-content.s3.amazonaws.com/datasets/rappiplus_orders_raw.csv
https://practicum-content.s3.amazonaws.com/datasets/rappiplus_catalog.csv
https://practicum-content.s3.amazonaws.com/datasets/rappiplus_marketing_spend.csv

## 📂 Dataset del proyecto (Funnel y Cohortes)

Fuente de datos
Para este análisis se utilizará la siguiente tabla:

events, que se encuentra almacenada en una base de datos.
⚙️ Importante: La conexión a esta base de datos se realizará desde el Jupyter Notebook

Tabla users → Información de registro de usuarios.
Tabla user_activity → Actividad de los usuarios después del registro.

## 📂 Dataset del proyecto (A/B Testing)
Para este análisis se utilizará la siguiente tabla:

📄 /datasets/experiment_checkout_ui.csv
https://practicum-content.s3.amazonaws.com/datasets/experiment_checkout_ui.csv

Cada fila representa la participación de un usuario en un experimento (A/B testing).


## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](URL_DEL_NOTEBOOK_EN_GITHUB)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/everpeak_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Generar insights para el equipo de Rappi Plus mediante Tableros de Power BI
