# 📶 Análisis de Consumo y Segmentación en Telecomunicaciones - ConnectaTel

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NzyMIMx9XDxf9-s51oe_xwSqpjfQvjk4)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/wasuarezm-cell/ConnectaTel-Analysis)

Este proyecto presenta un Análisis Exploratorio de Datos (EDA) que evalúa el comportamiento y los patrones de consumo de los usuarios de **ConnectaTel**. A través del procesamiento de datos históricos, este análisis identifica oportunidades de negocio para optimizar la oferta de planes y mejorar la rentabilidad.

## 🎯 Objetivo del Proyecto
Transformar datos crudos de clientes en *insights* estratégicos. El objetivo principal es identificar segmentos de usuarios según su comportamiento (uso bajo/medio/alto), detectar perfiles extremos (*Power Users*) y proponer recomendaciones comerciales basadas en datos para el catálogo de servicios.

## 📊 Datasets Utilizados
El análisis se basa en dos fuentes de datos principales:
- `users_latam.csv`: Información demográfica y de registro de los clientes.
- `usage.csv`: Registros detallados de consumo de minutos, llamadas y mensajes.

## 🚀 Etapas del Análisis
1. **Limpieza y Preprocesamiento:** Corrección de tipos de datos (formatos temporales), estandarización a `snake_case` y manejo de valores nulos.
2. **Ingeniería de Características (*Feature Engineering*):** Creación de nuevas categorías para segmentar usuarios por grupo de edad y niveles de consumo.
3. **Análisis Estadístico y Visual:** Aplicación de gráficos (histogramas, *boxplots*, barras) para identificar distribuciones, asimetrías y valores atípicos (*outliers*).
4. **Conclusiones Estratégicas:** Traducción de hallazgos técnicos en recomendaciones de negocio (estrategias de *upselling*, reestructuración de beneficios y detección de canales obsoletos).

## ▶ Cómo ejecutar el Notebook
Para visualizar y ejecutar el análisis, tienes dos opciones:

1. **Google Colab (Recomendado):**
   Haz clic en el botón a continuación para abrirlo directamente en tu navegador:
   
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NzyMIMx9XDxf9-s51oe_xwSqpjfQvjk4)

2. **Localmente:**
   - Clona este repositorio: `git clone https://github.com/wasuarezm-cell/ConnectaTel-Analysis`
   - Asegúrate de tener instaladas las librerías necesarias: `pandas`, `seaborn`, `matplotlib`.

## 📘 Guía de Reproducción
1. Asegúrate de tener los archivos `users_latam.csv` y `usage.csv` en una carpeta llamada `/datasets/`.
2. Abre el notebook `proyecto_connectatel.ipynb`.
3. Ejecuta las celdas en orden secuencial (Kernel > Restart & Run All).
