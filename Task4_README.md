# 🛒 Real-World Data Project — Retail Sales Analysis

**Internship:** Data Science Internship @ [Thiranex](https://thiranex.in)
**Author:** Ankita Kumari
**Task:** 4 of 4 — Real-World Data Project (Retail)

## 📌 Project Overview

This project analyzes a **real-world retail sales dataset** (Superstore dataset) to uncover business insights related to sales, profit, product categories, and customer purchasing patterns. The goal was to apply data science skills in a domain-specific, business-oriented context.

## 🎯 Objectives

- Analyze retail sales data and understand business performance
- Identify top-performing product categories
- Evaluate profit generation across different categories
- Discover sales trends and patterns
- Perform statistical analysis on sales-related data
- Generate business insights through data visualization

## 🗂️ Dataset

**Domain:** Retail
**Key columns:**

| Column | Description |
|--------|-------------|
| `Order ID` | Unique identifier for each order |
| `Category` | Main product category (Furniture, Office Supplies, Technology) |
| `Sub-Category` | Specific product type within a category |
| `Sales` | Revenue generated from sales |
| `Profit` | Profit earned per transaction |
| `Quantity` | Number of units sold |
| `Region` | Geographical region of the order |
| `Order Date` | Date the order was placed |

## 🔎 Analysis Performed

- Dataset inspection using `.info()` — structure, data types, missing values
- Statistical summary using `.describe()` — mean, median, std dev, quartiles
- Category-wise and product-wise performance analysis
- Correlation analysis between Sales, Profit, and Quantity

## 📊 Visualizations Created

1. **Sales by Category** — revenue comparison across product categories
2. **Profit by Category** — profitability comparison across categories
3. **Top 10 Products by Sales** — best-performing sub-categories
4. **Sales Distribution** — histogram of transaction sales values
5. **Correlation Heatmap** — relationships between Sales, Profit & Quantity

## 🔍 Key Insights

- Certain product categories generated **significantly higher sales** than others
- **High sales didn't always mean high profit** — profitability varied across categories
- A **small number of products drove a large share of total revenue**
- Sales data was **unevenly distributed**, with a few high-value transactions
- Correlation analysis revealed meaningful relationships between **Sales, Quantity, and Profit**

## 💡 Business Recommendations

- Focus marketing & inventory efforts on high-performing categories
- Re-evaluate strategy for categories with high sales but low profit
- Improve stock availability for top-selling products
- Use sales trends for better demand forecasting
- Track profitability alongside revenue, not in isolation

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** & **NumPy** — data inspection & analysis
- **Matplotlib** & **Seaborn** — visualizations
- **Kaggle Notebook** — development environment

## 📁 Repository Structure

```
├── task4-internship.ipynb       # Jupyter notebook with full analysis
├── Real_World_Retail_Project_Report.docx   # Detailed project report
└── README.md                     # Project summary (this file)
```

## ▶️ How to Run

1. Clone this repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open `task4-internship.ipynb` in Jupyter Notebook / Google Colab / Kaggle
4. Run all cells

## ✅ Outcome

This project applied data science skills to a **real-world retail business problem**, strengthening the ability to translate data analysis into actionable business recommendations.

---
*This project was completed as part of the Data Science Internship at [Thiranex](https://thiranex.in).*
