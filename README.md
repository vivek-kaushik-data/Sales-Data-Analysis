# 📊 Sales Data Analysis

End-to-end sales data analysis performed on a structured dataset to extract meaningful business insights using Python and its libraries.

---

## 📁 Project Structure
sales-data-analysis/
├── Data/
│   ├── sales_messy.csv        # Raw uncleaned dataset
│   └── sales_cleaned.csv      # Cleaned and processed dataset
├── Notebooks/
│   └── Analysis.ipynb         # Complete analysis notebook
└── README.md
---

## 🎯 Objective

To perform a complete sales data analysis including data cleaning, feature engineering, exploratory data analysis, and visualization to derive actionable business insights.

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive development environment |

---

## 🔄 Project Workflow

### 1. Data Cleaning
- Handled missing values
- Removed incorrect entries (zero and negative values)
- Fixed inconsistent text formats
- Eliminated duplicate records

### 2. Feature Engineering
- Created Revenue column (Price × Quantity)
- Extracted Month from date for time-based analysis
- Extracted Quarter for quarterly trend analysis

### 3. Exploratory Data Analysis (EDA)
- Revenue performance across regions, categories, and products
- Identified top revenue-generating products
- Regional comparison of sales performance
- Monthly and quarterly revenue trends

### 4. Data Visualization
- Bar charts for regional and product-level comparisons
- Line charts for monthly and quarterly trends

---

## 📈 Key Insights

- 💻 High-value products like laptops and tablets contribute the most to overall revenue
- 📦 Revenue is driven by pricing rather than quantity sold — lower-priced items generate less revenue despite similar sales volume
- 🌍 West region contributes the highest revenue
- 📉 South region contributes the least revenue and has the most growth potential
- 📅 Quarterly trends reveal consistent patterns useful for forecasting

---

## 💡 Business Recommendations

1. Focus on high-value products — prioritize marketing and stock availability for laptops and tablets
2. Improve South region performance — invest in targeted campaigns and regional strategies
3. Optimize pricing strategies — revisit pricing for lower-revenue products to improve margins
4. Leverage quarterly trends — plan inventory and promotions around peak sales periods

---

## 📂 Dataset Info

| File | Description |
|------|-------------|
| sales_messy.csv | Raw dataset with missing values, duplicates, and inconsistencies |
| sales_cleaned.csv | Processed dataset ready for analysis |

---

## 🚀 How to Run

1. Clone the repository
2. Open Notebooks/Analysis.ipynb in Jupyter Notebook
3. Run all cells sequentially

---

## 👤 Author

Vivek Kaushik 
[GitHub](https://github.com/vivek-kaushik-data) | [LinkedIn](https://www.linkedin.com/in/vivek-kaushik-cse)
