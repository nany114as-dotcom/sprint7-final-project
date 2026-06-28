# sprint7-final-project

**Análisis de Consumo ConnectaTel**
Este repositorio contiene el análisis estadístico y la segmentación de clientes realizados para la empresa de telecomunicaciones ConnectaTel. 

El dataset analizado incluye los registros de 4,000 usuarios con valores faltantes, valores atípicos (outliers) y problemas de calidad diseñados para simular un entorno real de análisis de datos.

📂 Contenido del repositorio

notebooks/analisis_connectatel.ipynb → Notebook principal con la limpieza de datos, análisis exploratorio (EDA), distribuciones, segmentación por grupos de uso y conclusiones estratégicas.
▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
Open In Colab

O también puedes:
1. Abrir el archivo .ipynb directamente aquí en GitHub.
2. Hacer clic en el botón Open in Colab que aparecerá en la parte superior.

📘 Cómo reproducir el análisis

Abre el archivo notebooks/analisis_connectatel.ipynb en Google Colab o Jupyter.
Ejecuta las celdas en orden secuencial.
El notebook está configurado para cargar los datos de manera automática y procesar las variables de consumo sin necesidad de configuraciones adicionales.
🧠 Objetivo del análisis

Identificar y corregir problemas de calidad: Limpieza de datos, gestión de nulos y tratamiento de registros duplicados en la base de clientes.
Analizar el comportamiento demográfico: Evaluar el impacto de variables como la edad en el consumo de red (identificando promedios homogéneos de ~4.5 llamadas y ~5.5 mensajes entre generaciones).
Estudiar distribuciones y anomalías: Analizar el solapamiento de los planes Básico y Premium (picos de 4 a 6 interacciones) e identificar llamadas de duración extrema (hasta 155 minutos).
Segmentación basada en datos: Clasificar a la base de usuarios en perfiles cuantitativos (Bajo Uso, Uso Medio y Alto Uso) para generar recomendaciones directas al equipo de estrategia comercial de ConnectaTel.
