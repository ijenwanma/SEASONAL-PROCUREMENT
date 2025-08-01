# SEASONAL-PROCUREMENT
## Andhra Pradesh Agricultural Procurement Analysis (2020–2022)

This repository presents an Excel-based analysis of agricultural procurement data from Andhra Pradesh, India, covering multiple commodities, districts, and crop seasons. The goal is to uncover key insights to guide data-driven decisions in agricultural planning and policy.

---

## Dataset Overview

This dataset contains government procurement records for major crops across Andhra Pradesh districts between 2020 and 2022. It includes:

| Column             | Description |
|--------------------|-------------|
| `District`         | District name in Andhra Pradesh |
| `Commodity`        | Crop name (e.g., Maize, Bengal gram, Turmeric) |
| `Season`           | Crop season (e.g., Kharif-2020, Rabi 2021-22) |
| `Qty (MTs)`        | Quantity procured in metric tonnes |
| `No of Farmers`    | Number of farmers who sold the crop |
| `Amount (Rs)`      | Total amount paid for procurement |

---

## ❓ Key Business Questions & Insights

**1. Which crop generates the highest revenue per metric ton across districts and seasons?**  
→ Identifies the most **price-efficient** and **profitable** crops.

**2. Which district records the highest agricultural revenue, and what drives that success?**  
→ Reveals **high-performing regions** and the **contributing crops**.

**3. What is the relationship between quantity procured and revenue generated?**  
→ Helps validate if **higher quantity equals higher earnings**, or if pricing is a more critical factor.

**4. Which crop-season combinations offer the best return?**  
→ Pinpoints **optimal crop timing** for **maximum profitability**.

---

## 📊 Correlation Analysis

A Pearson correlation matrix was calculated between **quantity procured** and **procurement amount (₹)**:

|                          | Avg. Qty (MTs) | Avg. Amount (Rs) |
|--------------------------|----------------|------------------|
| **Avg. Qty (MTs)**       | 1              | 0.9319           |
| **Avg. Amount (Rs)**     | 0.9319         | 1                |

🔍 **Interpretation**:
- A **strong positive correlation (0.93)** indicates that higher quantities generally lead to higher total revenue.
- However, it's **not a perfect correlation**, suggesting **unit price variation** affects profitability across crops and regions.

---

## 🧰 Tools Used

- **Microsoft Excel**  
  - Pivot tables for aggregation
  - Charts for visualization
  - Correlation analysis
- **Coming Soon**: Python automation for deeper insights

---

## 📈 Sample Visuals (Not Included Here)
- Top crops by revenue per ton
- District-wise procurement heatmaps
- Crop-season profitability matrix

---

## 📬 Contact

Have suggestions, questions, or want to collaborate?  
Feel free to connect:

- **Author**: [Constance Ijeoma Welcome]
- **Email**: [ijenwanma@gmail.com]
- **LinkedIn**: [https://www.linkedin.com/in/constance-welcome]

---

> 📌 *This project is ideal for analysts exploring Excel-based insights in agriculture, especially those focusing on regional procurement performance.*
