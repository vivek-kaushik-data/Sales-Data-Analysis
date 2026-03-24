# 📊 Sales Data Analysis

End-to-end sales data analysis performed on a structured dataset of ~ 6,000 records to extract meaningful business insights using Python and its libraries.

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

| Tool             | Purpose                          |
|------------------|----------------------------------|
| Python           | Core programming language        |
| Pandas           | Data manipulation and cleaning   |
| NumPy            | Numerical computations           |
| Matplotlib       | Data visualization               |
| Jupyter Notebook | Interactive development environment |

---

## 🔄 Project Workflow

### 1. Data Cleaning
- Handled missing values across the dataset
- Corrected invalid entries (zero and negative prices)
- Standardized inconsistent categorical data
- Removed duplicate records to ensure data integrity

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

## 📈 Key Insights & Numbers

### 💰 Overall Revenue
| Metric | Value |
|--------|-------|
| Total Revenue | ₹525.8M+ |
| Total Records Analyzed | ~6,000 |

---

### 🛍️ Revenue by Category
| Category | Revenue | Units Sold |
|----------|---------|------------|
| Electronics | ~₹474M | 13,448 units |
| Fashion | ~₹51.7M | 12,966 units |

> 💡 Despite similar sales volumes, Electronics generates 9x more revenue than
> Fashion — proving that revenue is strongly driven by product pricing, not quantity.

---

### 🌍 Revenue by Region
| Region | Revenue | Performance |
|--------|---------|-------------|
| West | ~₹134M | 🏆 Highest |
| North | ~₹132M | 2nd |
| East | ~₹130M | 3rd |
| South | ~₹128M | 📉 Lowest |

> 💡 Regional distribution is relatively balanced, but South has the most
> room for growth.

---

### 💻 Product-Level Performance
| Product | Performance |
|---------|-------------|
| Laptops | 🏆 Top Revenue Driver |
| Tablets | 2nd Highest Revenue |
| Shoes | 📉 Lowest Revenue Contributor |

---

## 💡 Business Recommendations

1. Focus on High-Value Products — Prioritize marketing and stock availabilityfor Laptops and Tablets as they are the primary revenue drivers
2. Improve South Region Performance — Invest in targeted regional campaignsto close the gap with the West region (~₹6M difference)
3. Optimize Pricing for Fashion Category — Despite 12,966 units sold,Fashion contributes only ₹51.7M vs Electronics ₹474M — revisiting pricing strategy could significantly boost revenue
4. Leverage Quarterly Trends — Plan inventory and promotions aroundpeak sales periods identified in time-based analysis

---

## 📂 Dataset Info

| File | Description |
|------|-------------|
| sales_messy.csv | Raw dataset with missing values, duplicates, and inconsistencies |
| sales_cleaned.csv | Cleaned and processed dataset ready for analysis |

---

## 🚀 How to Run

1. Clone or download this repository
2. Open Notebooks/Analysis.ipynb in Jupyter Notebook
3. Run all cells sequentially

---

## 👤 Author

Vivek Kaushik
[GitHub](https://github.com/vivek-kaushik-data) | [LinkedIn](https://www.linkedin.com/in/vivek-kaushik-cse)
