# 📊 Dashboard de Performance Comercial: Superstore Analysis

## 🎯 Objetivo del Proyecto
Transformar un dataset de retail desordenado en una herramienta interactiva para la toma de decisiones. El enfoque principal fue realizar un proceso de **ETL en Power Query** y responder a 4 preguntas críticas sobre la salud financiera y operativa del negocio.

---

## 📂 Recursos del Proyecto
* **Dataset Utilizado:** https://github.com/sebaaa16/Analisis-ventas-rentabilidad-superstore/blob/main/Sample%20-%20Superstore.csv
* **Herramientas:** Power BI Desktop / Power Query.
* **Técnicas:** Limpieza de delimitadores, tipado de datos y cálculos con medidas DAX.

---

## ❓ Preguntas de Negocio Resueltas (KPIs)
Siguiendo un enfoque de análisis de datos profesional, el dashboard responde a:

1.  **Salud Financiera (KPIs):** ¿Cuál es el total de Ventas, la Ganancia total y el Margen de beneficio promedio?
    * *Solución:* Implementación de **Cards (Tarjetas)** dinámicas con medidas DAX.
2.  **Rendimiento por Categoría:** ¿Qué categorías generan más ingresos y cuáles son realmente las más rentables?
    * *Solución:* **Gráfico de barras agrupadas** para contrastar volumen de venta vs. rentabilidad.
3.  **Análisis Geográfico:** ¿Cómo se distribuyen las ventas a lo largo del territorio nacional por estado?
    * *Solución:* **Mapa de burbujas** titulado "Distribución geográfica de ventas por estado".
4.  **Evolución Temporal:** ¿Hay algún mes o día del año donde las ventas caigan drásticamente?
    * *Solución:* **Gráfico de líneas de tendencia** detallado por fecha.

---

## 🖼️ Dashboard Final
Aca podes ver el resultado de la visualización:

https://github.com/sebaaa16/Analisis-ventas-rentabilidad-superstore/blob/main/Dashboard.PNG

---

## 🛠️ Mi Proceso de Trabajo (ETL con Power Query)
Como los datos originales presentaban errores de formato y columnas amontonadas, realicé los siguientes pasos:
* **Separación de Columnas:** Corregí el archivo CSV original aplicando delimitadores por coma.
* **Limpieza de Formatos:** Ajusté las columnas de Ventas y Ganancia a formato "Número Decimal Fijo" para asegurar la exactitud de los cálculos.
* **Cálculos DAX:** Creé la medida clave `Margen = DIVIDE(SUM('Sample - Superstore'[Profit]), SUM('Sample - Superstore'[Sales]))` para monitorear la rentabilidad real de cada operación.
* **UI/UX:** Diseñé un panel de filtros lateral para permitir una navegación fluida por región, año y categoría.

---

## 💡 Insights Clave 
* **Salud Financiera:** Se determinó que el **Margen de Beneficio promedio es del 12,47%**, un indicador sólido para el sector de retail, aunque con variaciones importantes entre categorías.
* **Visibilidad Geográfica:** El mapa permitió identificar rápidamente qué estados concentran el mayor volumen de facturación, facilitando la detección de mercados clave.
* **Optimización de Inventario:** Gracias al gráfico de evolución temporal, se identificaron los picos de demanda estacionales, permitiendo una mejor planificación de stock y logística.


--
*Desarrollado por [Tu Nombre] - Junior Data Analyst
