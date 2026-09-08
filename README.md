# Amazon Products Sales Analysis (2025) 🛒

## 📌 Project Overview

This project analyzes Amazon electronics product data collected in 2025 to identify patterns in pricing, discounts, customer ratings, customer engagement, product positioning, and category performance.

The project was developed as part of the NTI Data Analytics & Business Intelligence training.

## 📊 Dataset

- Records: 42,675
- Features: 16
- Data Source: Amazon Product Data
- Year: 2025

## 🎯 Business Questions

The analysis focuses on four main business questions:

1. **Pricing**  
   How does pricing vary across products and price segments?

2. **Discounts**  
   How are discounts distributed across products, and what patterns can be observed?

3. **Customer Engagement**  
   What patterns exist between product ratings, reviews, and customer engagement?

4. **Product Performance**  
   Which products or categories stand out as opportunities or areas requiring attention?

## 🔄 Analytical Workflow

Raw Data  
↓  
Data Cleaning  
↓  
Feature Engineering  
↓  
Exploratory Data Analysis  
↓  
Statistical Analysis  
↓  
Power BI  
↓  
Business Insights

## 🧹 Data Cleaning & Preprocessing

The data preparation process included:

- Missing value analysis
- Missing value handling
- Removal of highly missing columns
- Text and numeric cleaning
- Rating validation
- Review count validation
- Price validation
- Duplicate detection
- Negative value checks

### Data Quality Validation

- Duplicate Rows: 0
- Invalid Ratings: 0
- Negative Reviews: 0
- Negative Prices: 0

The dataset passed the main data-quality validation checks.

## ⚙️ Feature Engineering

### Discount Percentage

Discount percentage was calculated using:

`Discount % = ((Listed Price - Current Price) / Listed Price) × 100`

### Price Buckets

Products were categorized into:

- **Low:** 0–50
- **Medium:** 50–200
- **High:** >200

## 🐍 Python Exploratory Data Analysis

Python was used for:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Statistical Analysis
- Relationship Analysis
- Data Visualization

### Analysis Areas

- Price bucket distribution
- Product reviews
- Customer engagement
- Discount groups
- Product ratings
- Relationships between numerical variables

## 📈 Statistical Analysis

A statistical analysis was performed to investigate the relationship between customer engagement and discount groups.

### Results

- T-statistic: **-0.508**
- P-value: **0.612**

Since the p-value is greater than 0.05, the difference was not statistically significant.

Therefore, the analysis did not provide sufficient evidence that discount level significantly affects customer engagement.

## 📊 Power BI Dashboard

The analyzed data was transformed into interactive Power BI dashboards covering:

### Performance Overview

- Product performance
- Financial performance
- Ratings
- Discounts

### Finance & Profit

- Revenue
- Revenue by price bucket
- Discounted price analysis
- Sponsored vs. organic products

### Rating Analysis

- Average review rating
- Rating distribution
- Rating by brand
- Rating vs. discounted price

## 💡 Key Findings

- Medium-priced products dominate the catalog.
- Discount levels vary widely across products.
- Review volume is highly concentrated in a small number of accessory products.
- Average rating is approximately 4.4.
- Most ratings are concentrated between 4.0 and 5.0.
- The statistical analysis found no significant difference in customer engagement across discount groups.

## 💼 Business Recommendations

### Pricing Strategy
Monitor product segments and identify opportunities across low, medium, and high price ranges.

### Discount Strategy
Do not assume that higher discounts automatically generate higher customer engagement.

### Product Monitoring
Monitor products with strong ratings and customer engagement.

### Opportunity Identification
Identify products and categories combining strong customer satisfaction with strong engagement.

### Dashboard Monitoring
Use Power BI dashboards for continuous monitoring and business decision support.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statistical Analysis
- Power BI
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Business Intelligence

## 👥 Team

- Hazem Ahmed Farouk
- Mahmoud Mohamed Kosbar
- Asmaa Mohamed Elsayed
- Safaa Yasser Abdallah
- Hager Mohamed Elhady

## 🎓 Training

**NTI Data Analytics & Business Intelligence — Final Project**

---

> Turning raw product data into clear, data-driven business decisions.
