# 📐 DAX Measures — Falabella Retail Analytics

---

### 📈 Ejecutivo
| Measure | Description |
|---------|-------------|
| `Total Ingresos Netos` | Total net revenue |
| `Total Ganancia` | Total profit |
| `Margen Bruto %` | Gross margin percentage |
| `Total Clientes Unicos` | Unique active customers |
| `Ingresos Variacion YoY %` | Net revenue YoY variance |
| `Margen Bruto Variacion YoY` | Gross margin YoY variance |
| `Total Ganancias YoY %` | Profit YoY variance |
| `Total Clientes Variacion YoY` | Customer count YoY variance |
| `Ingresos año anterior` | Prior year revenue for comparison |
| `Variacion MoM %` | Month-over-month revenue variance |
| `Media Movil 3M` | 3-month moving average of net revenue |
| `Proyeccion 3M` | 3-month forward revenue projection |
| `Descuento Promedio` | Average discount applied |
| `% Participacion Clientes` | Customer share over total base |

---

### 🃏 KPIs — HTML Content Cards
| Measure | Description |
|---------|-------------|
| `HTML Ingresos Netos` | Styled KPI card — net revenue + YoY delta |
| `HTML Total Ganancia` | Styled KPI card — total profit + YoY delta |
| `HTML Margen Bruto` | Styled KPI card — gross margin % + YoY delta |
| `HTML Clientes Unicos` | Styled KPI card — unique customers + YoY delta |
| `HTML Proyeccion 3M` | Styled KPI card — 3M projection vs target |

---

### 🏷️ Ventas y Productos
| Measure | Description |
|---------|-------------|
| `Margen Neto` | Net margin per product/category |
| `Participacion Producto %` | Product revenue share over total |
| `Rank Categoria` | Category ranking by revenue |
| `acumulado Categoria` | Cumulative revenue by category |
| `Pareto Categoria` | Cumulative % for Pareto analysis |
| `Pareto Umbral` | 80% threshold reference line |
| `Clasificacion ABC` | ABC classification by revenue contribution |
| `Clasificacion XYZ` | XYZ classification by demand variability |
| `Clasificacion ABCXYZ` | Combined ABC+XYZ matrix classification |
| `Clasificacion filtrada` | Dynamic classification based on active filters |
| `CV Trimestral` | Quarterly coefficient of variation |
| `Media Por Categoria Trimestral` | Quarterly average revenue per category |
| `Desviacion Por Categoria Trimestral` | Quarterly standard deviation per category |

---

### 👤 Clientes — RFM
| Measure | Description |
|---------|-------------|
| `Recency Dias` | Days since last purchase |
| `Frecuencia` | Purchase frequency per customer |
| `Monetary` | Total spend per customer |
| `AOV` | Average Order Value |
| `RFM SCORE Recency` | Recency score (1–5) |
| `RFM Score Frecuencia` | Frequency score (1–5) |
| `RFM SCORE Monetary` | Monetary score (1–5) |
| `Suma Score RFM` | Combined RFM score |
| `Clasificacion Cliente` | Customer segment label (Champion, At Risk, etc.) |
| `Evolucion Retencion Cliente` | Customer retention trend over time |

---

### ⚠️ Anomalías
| Measure | Description |
|---------|-------------|
| `Media Ingreso Mensual` | Monthly average revenue baseline |
| `Desviacion Estandar Ingresos` | Standard deviation of monthly revenue |
| `Limite Superior` | Upper control band (mean + 2σ) |
| `Limite Inferior` | Lower control band (mean − 2σ) |
| `% Tasa de Devolucion` | Product return rate percentage |
| `Benckmark Devolucion` | Return rate benchmark reference |
| `KPI M.Bruto` | Gross margin KPI for anomaly context |
| `Metricas` | Dynamic metric selector (field parameter) |
