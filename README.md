# 📊 Análisis de Ventas y Rentabilidad - Retail Dashboard

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es analizar el desempeño comercial de una tienda minorista (Superstore) para identificar patrones de venta, medir la rentabilidad real por categoría y optimizar la toma de decisiones basada en datos geográficos y temporales.

---

## 📂 Recursos del Proyecto
* **Data Set Utilizado:** [Descargar Dataset Aquí](Data/superstore_cleaned.csv) *(Asegúrate de que la ruta sea correcta)*
* **Herramienta de Visualización:** Power BI Desktop.
* **Procesamiento de Datos:** PostgreSQL / Power Query.

---

## ❓ Preguntas de Negocio (KPIs)
Para guiar el análisis, respondimos las siguientes preguntas clave:
1. ¿Cuál es el **Margen de Ganancia** global y por categoría?
2. ¿Qué estados presentan pérdidas a pesar de tener ventas altas?
3. ¿Cómo evolucionan las ventas en una escala de **tiempo diaria**?
4. ¿Cuáles son las **Top 10 Subcategorías** que más ingresos generan?
5. ¿Qué segmento de cliente (Consumidor, Corporativo, etc.) es el más rentable?

---

## 🖼️ Dashboard Preview
Aquí puedes ver una captura del tablero interactivo finalizado:

![Dashboard Preview](Report/dashboard_screenshot.png)

---

## 🛠️ Proceso de Análisis
1.  **Extracción:** Importación del dataset CSV original.
2.  **Limpieza (ETL):** Uso de SQL y Power Query para corregir formatos de fecha, moneda y escalas de magnitud.
3.  **Modelado:** Creación de medidas DAX para calcular el % de margen y total de beneficios.
4.  **Visualización:** Diseño de interfaz con panel de filtros lateral para interactividad total.

---

## 💡 Insights y Conclusiones
* **Rentabilidad Crítica:** Aunque las ventas son altas, el margen promedio es del **2.49%**. La categoría de Muebles es la que más afecta negativamente este número.
* **Oportunidad Geográfica:** El estado de California es el motor de ventas, pero se detectaron estados en la región "Central" con retornos negativos.
* **Eficiencia de Segmento:** El segmento "Consumer" representa la mayor parte de los ingresos, permitiendo enfocar campañas de marketing específicas.

---

## 🏁 Conclusión Final
Este análisis demuestra que el volumen de ventas no siempre equivale a éxito financiero. Se recomienda revisar la estructura de costos y descuentos en la categoría de Muebles para elevar el margen neto del negocio.

---
*Desarrollado por [Tu Nombre] - Junior Data Analyst*
