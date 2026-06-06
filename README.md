# 🛍️ Falabella Retail Analytics Dashboard — Power BI

> Retail analytics dashboard built in Power BI, modeled after Falabella's
> commercial operations. Covers executive performance, product segmentation,
> customer behavior (RFM), and anomaly detection across physical and
> e-commerce channels.

---

## 📌 Overview

This dashboard enables end-to-end retail analysis across four analytical
dimensions: executive KPIs with YoY and MoM variance, product classification
(ABC/XYZ/ABCXYZ), customer segmentation via RFM scoring, and statistical
anomaly detection using standard deviation bands and return rate benchmarks.
Built with advanced DAX patterns, HTML Content KPI cards, and slicers for
Categoría, Segmento, Canal, and Año.

---

## 📊 Dashboard Pages

| Page | Focus |
|------|-------|
| 📈 Vista Ejecutiva | Revenue, profit, margin, 3M projection, moving average |
| 🏷️ Comportamiento Productos | ABC/XYZ classification, Pareto, category ranking |
| 👤 Comportamiento Clientes | RFM segmentation, AOV, retention, frequency |
| ⚠️ Anomalías | Return rate, deviation bands, income anomaly detection |

---

## 📐 DAX Measures

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

### 🃏 KPIs — HTML Content Cards
| Measure | Description |
|---------|-------------|
| `HTML Ingresos Netos` | Styled KPI card — net revenue + YoY delta |
| `HTML Total Ganancia` | Styled KPI card — total profit + YoY delta |
| `HTML Margen Bruto` | Styled KPI card — gross margin % + YoY delta |
| `HTML Clientes Unicos` | Styled KPI card — unique customers + YoY delta |
| `HTML Proyeccion 3M` | Styled KPI card — 3M projection vs target |

### 🏷️ Ventas y Productos
| Measure | Description |
|---------|-------------|
| `Total Ingresos Netos` | Base revenue for product analysis |
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

---

## 🛠 Tech Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard design and publishing |
| DAX | All calculated measures, KPIs, and classifications |
| SQL Server | Data source and transformations |
| Python | ETL pipeline and synthetic data generation |
| HTML Content (DAX) | Custom styled KPI cards |

---

## 📁 Repository Structure

```
falabella-retail-analytics-powerbi/
│
├── assets/
│   ├── ejecutivo.png
│   ├── productos.png
│   ├── clientes.png
│   └── anomalias.png
│
├── dax/
│   └── measures.md
│
├── data/
│   └── (source files or SQL scripts)
│
└── README.md
```

---

## 📸 Preview

> Screenshots of each dashboard page go here.

---

## 👤 Author

**Diego Torres Andrade**
Systems Engineering Student — Universidad Privada del Norte
Specialization: Data Analytics & Business Intelligence

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/tu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/tu-usuario)
