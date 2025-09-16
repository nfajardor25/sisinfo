# Proyecto de Análisis de Ventas - Techstore

Este proyecto analiza las ventas de la empresa **Techstore** utilizando **Power BI** y **Tableau**, comparando el desempeño de ambas herramientas de BI en términos de visualización, modelado de datos y análisis.

---

## 📊 KPIs Analizados
- **Ventas Totales**
- **Cumplimiento de la Meta (%)**
- **Crecimiento frente al mes anterior**
- **Ticket Promedio**
- **Participación de Cliente Premium**
- **Top 10 productos**
- **Performance por vendedor**

---

## 📈 Resultados en Power BI
- **Gráfica de líneas**: Evolución de ventas diarias y mensuales.
- **Gráfica de barras**: Top 10 productos más vendidos.
- **Gráfica circular**: Distribución de ventas por categoría.
- **Tablas**: Performance de vendedores y clientes Premium.
- **Medidas DAX**: Se implementaron fórmulas personalizadas (`SUMX`, `DIVIDE`, `LOOKUPVALUE`) para calcular KPIs.

---

## 📉 Resultados en Tableau
- **Dashboard con múltiples hojas**: Integración de ventas, metas y clientes.
- **Filtros interactivos**: Posibilidad de segmentar por periodo, producto o cliente.
- **Gráficas dinámicas**:
  - Ventas por mes.
  - Cumplimiento de la meta mensual.
  - Crecimiento de ventas vs mes anterior.
  - Ticket promedio.
- **Campos calculados** en Tableau replicaron la lógica de DAX (ej. `IFNULL`, `LOOKUP`, `COUNTD`).

---

## ⚖️ Comparativa Power BI vs Tableau

| Aspecto                  | Power BI 🟡                               | Tableau 🔵                               |
|---------------------------|-------------------------------------------|------------------------------------------|
| **Facilidad de uso**     | Más intuitivo para principiantes.          | Requiere curva de aprendizaje inicial.   |
| **Modelado de datos**    | Muy potente con DAX y relaciones directas. | Relacional, pero más visual y flexible.  |
| **Velocidad**            | Rápido en conjuntos pequeños y medianos.   | Muy eficiente en dashboards interactivos. |
| **Visualizaciones**      | Amplia variedad de gráficos estándar.      | Más personalización y estilo visual.     |
| **Interactividad**       | Buena, pero menos fluida.                  | Dashboards más dinámicos e interactivos. |
| **Licenciamiento**       | Tiene versión gratuita y Pro de pago.      | Tableau Public gratuito (limitado).      |

---

## 📝 Conclusiones
- **Power BI** resultó ideal para crear medidas con DAX y obtener KPIs de manera precisa y rápida.  
- **Tableau** brilló en la presentación visual y en la interactividad de los dashboards.  
- Ambas herramientas permitieron validar resultados y garantizar la consistencia de los cálculos.  

📌 En general: **Power BI** es más amigable para el análisis de datos, mientras que **Tableau** es más potente para la visualización interactiva.  
