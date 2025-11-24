# Aus Apparel Sales (4th Quarter) — Data Analysis Project

This project is part of my **AI/ML coursework**, where I performed exploratory data analysis (EDA) on the `AusApparelSales4thQtr.csv` dataset.  
The goal was to clean the data, analyze sales trends, visualize quarterly performance, and derive insights that could support sales forecasting and business decision-making.

---

## Project Overview

This notebook walks through the full data exploration workflow, including:

- Loading, inspecting, and understanding the dataset  
- Cleaning missing or inconsistent values  
- Generating descriptive statistics  
- Visualizing distributions and relationships  
- Identifying seasonal trends in sales  
- Detecting outliers and business anomalies  
- Summarizing findings and recommendations  

This project builds foundational skills in **data wrangling**, **EDA**, and **data visualization**, which are essential for preparing data for machine learning.

---

## Dataset Description

**File:** `AusApparelSales4thQtr.csv`  

**Common Columns Include:**
- `Date`
- `Store`
- `Category`
- `Units_Sold`
- `Unit_Price`
- `Total_Sales`
- `Region`

(Data may vary depending on the version provided.)

---

## Data Cleaning Steps

The notebook includes several preprocessing steps:

- Handling missing values  
- Converting `Date` to a proper datetime format  
- Fixing numeric and categorical data types  
- Removing or analyzing outliers  
- Creating new engineered features such as:
  - **Month**
  - **Week**
  - **Sales per Unit**
  - **Season Indicators**
- Ensuring dataset readiness for future ML tasks  

---

## Visualizations Included

This project includes several high-impact visualizations:

### **Distribution & Summary Charts**
- Histogram of Total Sales  
- Boxplot for outlier detection  
- Density/Distribution plots  

### **Time-Based Visuals**
- Sales by Day  
- Sales by Week  
- Month-over-Month performance  

### **Category-Level Insights**
- Total Sales by Apparel Category  
- Category contribution to overall revenue  

### **Regional Analysis**
- State-wise sales trends  
- Region-to-region sales comparison  

---

## Skills Demonstrated

- Data cleaning & wrangling with **pandas**  
- Exploratory data analysis  
- Statistical summaries and descriptive metrics  
- Data visualization with **Matplotlib** and **Seaborn**  
- Feature engineering  
- Interpreting trends for business insights  

---

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3** | Core programming language |
| **Pandas** | Data cleaning, wrangling, and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical plotting |
| **Jupyter Notebook** | Interactive analysis environment |

---

## How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/desiree2290/<REPO-NAME>.git
