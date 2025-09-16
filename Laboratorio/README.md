# Proyecto de Análisis de Ventas - Techstore

Este proyecto analiza las ventas de la empresa **Techstore** utilizando **Power BI** y **Tableau**, comparando el desempeño de ambas herramientas de BI en términos de visualización, modelado de datos y análisis.

---

## KPIs Analizados
- **Ventas Totales**
- **Cumplimiento de la Meta (%)**
- **Crecimiento frente al mes anterior**
- **Ticket Promedio**
- **Participación de Cliente Premium**
- **Top 10 productos**
- **Performance por vendedor**

---

##  Resultados en Power BI
- **Gráfica de líneas**: Evolución de ventas diarias y mensuales.
- **Gráfica de barras**: Top 10 productos más vendidos.
- **Gráfica circular**: Distribución de ventas por categoría.
- **Tablas**: Performance de vendedores y clientes Premium.
- **Medidas DAX**: Se implementaron fórmulas personalizadas (`SUMX`, `DIVIDE`) para calcular KPIs.

---

##  Resultados en Tableau
- **Dashboard con múltiples hojas**: Integración de ventas, metas y clientes.
- **Filtros interactivos**: Posibilidad de segmentar por periodo, producto o cliente.
- **Gráficas dinámicas**:
  - Ventas por mes.
  - Cumplimiento de la meta mensual.
  - Crecimiento de ventas vs mes anterior.
  - Ticket promedio.
- **Campos calculados** en Tableau replicaron la lógica de DAX (ej. `IFNULL`, `COUNTD`).

---

##  Comparativa Power BI vs Tableau

| Aspecto                  | Power BI                                | Tableau                              |
|---------------------------|-------------------------------------------|------------------------------------------|
| **Facilidad de uso**     | Más intuitivo para principiantes.          | Es más complejo, relacionar modelos se torna tedioso.   |
| **Modelado de datos**    | Muy potente con DAX y relaciones directas. | Más visual y flexible.  |
| **Velocidad**            | Rápido en conjuntos pequeños y medianos.   | Muy eficiente en dashboards interactivos. |
| **Visualizaciones**      | Amplia variedad de gráficos estándar.      | Más personalización y estilo visual.     |

---

##  Conclusiones
- **Power BI** resultó ideal para crear medidas con DAX y obtener KPIs de manera precisa y rápida, es más fácil de usar para alguien que nunca ha interactuado con él antes.  
- **Tableau** Tiene buena presentación visual y en la interactividad de los dashboards, mas sinembargo, relacionar las tablas (crear el modelo) fue más dificil que en power BI.  
- Ambas herramientas permitieron validar resultados y garantizar la consistencia de los cálculos.  

