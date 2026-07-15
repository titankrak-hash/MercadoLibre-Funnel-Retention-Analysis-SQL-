# MercadoLibre Funnel & Retention Analysis (SQL)

SQL project focused on conversion funnel analysis and user retention for MercadoLibre.

---

# 📂 Project Files

### 📊 SQL Queries
➡️ **https://github.com/titankrak-hash/MercadoLibre-Funnel-Retention-Analysis-SQL-/blob/main/Pasos%20que%20se%20realizaron%20en%20SQL%20explicados/New%20Text%20Document%20(2).txt**

### 📂 Excel del proyecto, informe ejecutivo. contexto, hallazgo e implicacion 
**https://github.com/titankrak-hash/MercadoLibre-Funnel-Retention-Analysis-SQL-/raw/refs/heads/main/Proyecto%204_%20An%C3%A1lisis%20de%20embudo%20y%20retenci%C3%B3n%20para%20MercadoLibre%20-%20Resumen%20ejecutivo%20(1).xlsx**


# Business Objective

Analyze MercadoLibre's conversion funnel and user retention to identify where users abandon the purchasing process and evaluate long-term engagement.

The project answers two main business questions:

- Where are users dropping off during the purchase funnel?
- How well are users retained over time?

---

# Dataset

The analysis uses two datasets:

- **mercadolibre_funnel**
  - User events throughout the purchase process.
  - Funnel stages from first visit to purchase.

- **mercadolibre_retention**
  - User activity after signup.
  - Cohort retention analysis.

---

# Funnel Stages

The conversion funnel analyzed is:

1. First Visit
2. Select Item / Promotion
3. Add to Cart
4. Begin Checkout
5. Add Shipping Information
6. Add Payment Information
7. Purchase

---

# SQL Skills Demonstrated

- Common Table Expressions (CTEs)
- JOINs
- Aggregations
- CASE WHEN
- Window Functions
- Cohort Analysis
- Funnel Analysis
- Conversion Rate Calculation
- Retention Analysis
- Data Validation (QA)

---

# Business Questions Answered

### Funnel Analysis

- Conversion rate between every funnel stage.
- Largest user drop-off.
- Funnel performance by country.
- Funnel performance by device.
- Funnel performance by referral source.

### Retention Analysis

- D7 Retention
- D14 Retention
- D21 Retention
- D28 Retention
- Retention comparison by country.

---

# Executive Insights

The SQL analysis identifies:

- Highest abandonment stage.
- Countries with strongest conversion.
- Countries with weakest conversion.
- User retention trends.
- Opportunities to improve product performance.

---

# Repository Structure

```
mercadolibre-funnel-retention-analysis/
│
├── README.md
├── queries.sql
└── (optional images)
```

---

# Tools Used

- SQL
- PostgreSQL
- Git
- GitHub

---

# Author

**Sebastian**
Data Analytics Portfolio
