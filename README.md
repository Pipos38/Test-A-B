# Análisis de hipótesis y test A/B para tienda online

Este proyecto simula un caso real en una tienda online. El objetivo es identificar las hipótesis de negocio más prometedoras para aumentar los ingresos y analizar los resultados de un experimento A/B implementado para validar una de ellas.

## 🔍 Objetivo del proyecto

1. Priorizar 9 hipótesis de negocio utilizando los frameworks **ICE** y **RICE**.
2. Realizar un análisis estadístico completo de un experimento **A/B** con datos reales.
3. Visualizar y analizar los resultados acumulados en términos de ingresos, tamaño de pedidos y tasa de conversión.
4. Identificar outliers y validar los resultados filtrando datos.
5. Emitir una recomendación basada en evidencia.

## 📁 Este repositorio contiene:

├── EDA_AB_Test.ipynb           # Notebook principal con el análisis completo  
├── hypotheses_us.csv           # Hipótesis con métricas ICE y RICE  
├── orders_us.csv               # Datos de pedidos por usuario  
├── visits_us.csv               # Datos de visitas diarias por grupo  
├── requirements.txt            # Librerías necesarias para ejecutar el notebook  
└── README.md                   # Descripción del proyecto  

## 🧠 Análisis realizado

- Priorización con ICE y RICE: comparación de criterios y resultados.
- Ingreso acumulado por grupo (A vs B).
- Tamaño promedio del pedido acumulado.
- Tasa de conversión diaria.
- Detección de valores atípicos usando percentiles 95 y 99.
- Pruebas de significancia estadística (Mann–Whitney U test) en:
  - Conversión (sin y con filtrado)
  - Tamaño del pedido (sin y con filtrado)
- Conclusión basada en los datos y visualizaciones.

## 🛠️ Herramientas utilizadas

- `Python`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy.stats`
- `Jupyter Notebook`

## ✅ Conclusión

[🔸Aquí puedes escribir un breve resumen de tu conclusión basada en los resultados del test A/B. Por ejemplo:  
*"El grupo B mostró una mejora estadísticamente significativa en la tasa de conversión, lo que sugiere que la nueva funcionalidad podría tener un impacto positivo en los ingresos si se implementa a gran escala."*]

---



