# 📊 Exploratory Data Analysis (EDA) Project

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a sales dataset using Python.
The goal is to analyze sales performance, identify trends, detect patterns, and extract meaningful business insights through statistical analysis and visualization.

---

## 🎯 Objectives

* Understand the dataset structure and variables
* Handle missing values and clean the dataset
* Analyze sales trends across products and regions
* Detect patterns, anomalies, and outliers
* Generate insights using data visualization

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Dataset Information

The dataset contains the following columns:

* Order_ID
* Product
* Region
* Units_Sold
* Unit_Price
* Year

A new column named **Total_Sales** was created using:

Total_Sales = Units_Sold × Unit_Price

---

## 📊 Analysis Performed

### ✅ Data Cleaning

* Checked missing values
* Filled missing values in Units_Sold column
* Created Total_Sales column

### ✅ Exploratory Data Analysis

* Product-wise sales analysis
* Region-wise sales analysis
* Yearly sales trend analysis
* Correlation analysis
* Outlier detection

### ✅ Visualizations Created

* Sales by Product
* Sales by Region
* Sales Trend Over Years
* Units Sold Distribution
* Correlation Heatmap
* Outlier Detection Boxplot

---

## 📈 Key Insights

* Certain products generate significantly higher revenue than others.
* Some regions outperform others in total sales contribution.
* Sales trends indicate business growth over the years.
* Outliers exist in units sold data.
* Unit price influences total sales generation.

---

## 📁 Project Structure

CodeAlpha_EDA/
│
├── data/
│   └── SalesDataset.csv
│
├── notebook/
│   └── eda_analysis.ipynb
│
├── images/
│   ├── sales_by_product.png
│   ├── sales_by_region.png
│   ├── sales_trend.png
│   ├── heatmap.png
│   └── distribution.png
│
├── insights/
│   └── insights.txt
│
├── README.md


---

## 🚀 Conclusion

This project demonstrates how raw business data can be transformed into actionable insights using Exploratory Data Analysis techniques and visualization tools.

The analysis helps understand product performance, regional trends, and sales behavior to support data-driven decision making.

---

## 👨‍💻 Author

Haarish

---

## 📌 Internship

Submitted as part of the Data Analytics Internship at CodeAlpha.
