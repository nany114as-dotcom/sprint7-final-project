# sprint7-final-project

**Análisis de Consumo ConnectaTel**

Este repositorio contiene el análisis estadístico y la segmentación de clientes realizados para la empresa de telecomunicaciones ConnectaTel. 

El proyecto integró tres datasets distintos: `plans.csv` (2 planes), `users_latam.csv` (4,000 usuarios) y `usage.csv` (40,000 registros de consumo), estos últimos dos con valores faltantes, valores atípicos (outliers) y problemas de calidad diseñados para simular un entorno real de análisis de datos."
## 📂 Contenido del repositorio

`S7_Version_Estudiante_Project_ConnectaTel.ipynb` → Notebook principal con la limpieza de datos, análisis exploratorio (EDA), distribuciones, visualizaciones gráficas segmentación por grupos de uso y conclusiones estratégicas.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CBKKHxdg1Vsm9XLmDuXlDrfwCcuKr4wr?usp=sharing)

O también puedes:
1. Abrir el archivo `.ipynb` directamente aquí en GitHub.
2. Hacer clic en el botón **Open in Colab** que aparecerá en la parte superior.

## 📘 Cómo reproducir el análisis

1. Abre el archivo  en Google Colab `S7_Version_Estudiante_Project_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden secuencial.
El notebook está configurado para cargar los datos de manera automática y procesar las variables de consumo sin necesidad de configuraciones adicionales.

## 🧠 Objetivo del análisis

* **Integración y limpieza de datos:** Consolidación y depuración de bases de datos para construir un dataset único de 4,000 usuarios apto para el análisis estadístico.
* **Validación y calidad de datos:** Aplicación de técnicas de validación, estandarización de tipos de datos, gestión de registros duplicados y tratamiento de valores nulos o inconsistentes.
* **Perfilado estadístico:** Construcción de perfiles de consumo cuantitativos (llamadas y mensajes) tanto a nivel general del negocio como desglosados por segmentos demográficos.
* **Detección de anomalías (*Outliers*):** Identificación y análisis de comportamientos atípicos mediante métodos estadísticos y visuales.
* **Segmentación avanzada de clientes:** Clasificación de la base de usuarios según criterios demográficos (rangos de edad) y patrones de comportamiento para definir grupos de volumen de uso (Bajo Uso, Uso Medio y Alto Uso).
* **Análisis visual e Insights de negocio:** Generación de histogramas y diagramas para visualizar el solapamiento de planes (Básico vs. Premium) y extraer recomendaciones estratégicas orientadas a la optimización de la oferta comercial.
