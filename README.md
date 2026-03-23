# 📊 Dashboard de Performance Comercial: Superstore Analysis

## 🎯 Objetivo del Proyecto
Transformar un dataset de retail desordenado en una herramienta interactiva para la toma de decisiones. El enfoque principal fue realizar un proceso de **ETL en Power Query** y responder a 4 preguntas críticas sobre la salud financiera y operativa del negocio.

---

## 📂 Recursos del Proyecto
* **Dataset Utilizado:** [Descargar Aquí](Data/superstore_cleaned.csv)
* **Herramientas:** Power BI Desktop / Power Query.
* **Técnicas:** Limpieza de delimitadores, tipado de datos y cálculos con medidas DAX.

---

## ❓ Preguntas de Negocio Resueltas (KPIs)
Siguiendo un enfoque de análisis de datos profesional, el dashboard responde a:

1.  **Salud Financiera (KPIs):** ¿Cuál es el total de Ventas, la Ganancia total y el Margen de beneficio promedio?
    * *Solución:* Implementación de **Cards (Tarjetas)** dinámicas con medidas DAX.
2.  **Rendimiento por Categoría:** ¿Qué categorías generan más ingresos y cuáles son realmente las más rentables?
    * *Solución:* **Gráfico de barras agrupadas** para contrastar volumen de venta vs. rentabilidad.
3.  **Análisis Geográfico:** ¿En qué estados o ciudades estamos perdiendo dinero (Ganancia negativa)?
    * *Solución:* **Mapa de burbujas** con formato condicional (Rojo para negativo / Verde para positivo).
4.  **Evolución Temporal:** ¿Hay algún mes o día del año donde las ventas caigan drásticamente?
    * *Solución:* **Gráfico de líneas de tendencia** detallado por fecha.

---

## 🖼️ Dashboard Final
Aquí puedes ver el resultado de la visualización:

![Vista del Tablero](Report/dashboard_screenshot.png)

---

## 🛠️ Mi Proceso de Trabajo (ETL con Power Query)
Como los datos originales presentaban errores de formato y columnas amontonadas, realicé los siguientes pasos:
* **Separación de Columnas:** Corregí el archivo CSV original aplicando delimitadores por coma.
* **Limpieza de Formatos:** Ajusté las columnas de Ventas y Ganancia a formato "Número Decimal Fijo" para asegurar la exactitud de los cálculos.
* **Cálculos DAX:** Creé la medida clave `Margen = DIVIDE(SUM(Profit), SUM(Sales))` para monitorear la rentabilidad real.
* **UI/UX:** Diseñé un panel de filtros lateral para permitir una navegación fluida por región, año y categoría.

---

## 💡 Insights Clave
* **Rentabilidad Crítica:** Se detectó un margen promedio global del **

---
*Desarrollado por [Tu Nombre] - Junior Data Analyst*
