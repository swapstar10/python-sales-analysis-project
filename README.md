# diwali-sales-analysis-python

# 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Diwali sales dataset to uncover customer purchasing behavior and business insights. Using Python and popular data analysis libraries, the dataset is cleaned, analyzed, and visualized to identify trends based on gender, age, state, occupation, marital status, and product categories.

The objective is to help businesses understand their customers and make data-driven decisions for targeted marketing and improved sales performance.

---

# 🎯 Business Problem

Retail businesses experience significant sales during the Diwali festival, but understanding customer buying patterns is essential for maximizing revenue.

This analysis aims to answer questions such as:

- Who are the most valuable customers?
- Which states contribute the highest sales?
- Which age groups spend the most?
- Which occupations generate the highest revenue?
- Which product categories are most popular?
- How does marital status influence purchasing behavior?

---

# 📂 Dataset Information

The dataset contains **11,251 customer transaction records** with **15 columns** before cleaning. :contentReference[oaicite:0]{index=0}

### Features

| Column | Description |
|---------|-------------|
| User_ID | Unique customer ID |
| Cust_name | Customer Name |
| Product_ID | Product Identifier |
| Gender | Customer Gender |
| Age Group | Customer Age Group |
| Age | Customer Age |
| Marital_Status | Marital Status |
| State | Customer State |
| Zone | Sales Zone |
| Occupation | Customer Occupation |
| Product_Category | Purchased Product Category |
| Orders | Number of Orders |
| Amount | Purchase Amount |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📋 Data Cleaning

The following preprocessing steps were performed:

- Imported the CSV dataset.
- Removed empty columns (`Status` and `unnamed1`).
- Checked for missing values.
- Removed records with null values.
- Converted the `Amount` column to integer.
- Verified data types and dataset structure.

These cleaning steps ensured the dataset was ready for analysis. :contentReference[oaicite:1]{index=1}

---

# 📊 Exploratory Data Analysis

The analysis includes the following visualizations:

## 1. Gender Distribution
**Visualization:** Count Plot

**Purpose:** Analyze the number of male and female customers.

**Business Insight:** Understand the gender composition of customers.

---

## 2. Sales by Gender
**Visualization:** Bar Chart

**Purpose:** Compare total purchase amount between male and female customers.

**Business Insight:** Identify which gender contributes more to overall sales.

---

## 3. Age Group Analysis
**Visualization:** Count Plot and Bar Chart

**Purpose:** Analyze customer distribution across age groups and identify which group spends the most.

**Business Insight:** Helps target marketing campaigns toward high-value age segments.

---

## 4. State-wise Sales
**Visualization:** Horizontal Bar Chart

**Purpose:** Identify states generating the highest revenue.

**Business Insight:** Helps prioritize regional marketing and inventory planning.

---

## 5. Marital Status Analysis
**Visualization:** Count Plot and Sales Comparison

**Purpose:** Compare purchasing behavior based on marital status.

**Business Insight:** Determine whether married or unmarried customers contribute more to sales.

---

## 6. Occupation Analysis
**Visualization:** Bar Chart

**Purpose:** Analyze spending by occupation.

**Business Insight:** Identify professions with higher purchasing power.

---

## 7. Product Category Analysis
**Visualization:** Bar Chart

**Purpose:** Determine the most popular product categories.

**Business Insight:** Helps optimize product assortment and inventory management.

---

## 8. Top Selling Products
**Visualization:** Bar Chart

**Purpose:** Identify products with the highest number of orders.

**Business Insight:** Supports demand forecasting and stock management.

---

# 📈 Key Insights

- Female customers contributed more to overall sales than male customers.
- Customers aged **26–35 years** represented the most valuable customer segment.
- Married women were among the highest spending customer groups.
- States such as Uttar Pradesh, Maharashtra, and Karnataka generated the highest sales.
- Customers working in IT, Healthcare, and Aviation sectors showed strong purchasing behavior.
- Food, Clothing, and Electronics were among the most popular product categories.

---

# 📁 Project Structure

```
Diwali-Sales-Analysis/
│
├── Dataset/
│   └── Diwali Sales Data.csv
│
├── Notebook/
│   └── Diwali_Sales_Analysis.ipynb
│
├── Images/
│   ├── gender_analysis.png
│   ├── age_group_analysis.png
│   ├── state_sales.png
│   ├── occupation_analysis.png
│   └── product_category.png
│
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/swapstar10/diwali-sales-analysis-python.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Diwali_Sales_Analysis.ipynb` and run all cells.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Customer Segmentation
- Business Insight Generation
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn
