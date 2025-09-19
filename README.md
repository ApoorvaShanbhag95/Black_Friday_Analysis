# 🛍️ Black Friday Sales Analysis & Prediction

An analysis project using historical retail data from Black Friday events to understand consumer behavior, drive pricing strategy, and build predictive models for purchase amounts.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) to understand customer demographics, purchasing patterns, and product category trends.  
- Determine which customer groups spend more (by age, gender, marital status, city tenure).  
- Build predictive models to forecast purchase amount for new transactions.  
- Provide insights & recommendations for pricing strategies to maximize profit while maintaining competitive sales.

---

## 🧰 Tools & Dataset

- **Dataset**: Analytics Vidhya “Black Friday” dataset (~537,577 rows, 12 features)  
- **Features analyzed**: age, gender, marital status, product categories, ‘stay in current city years’, etc.  
- **Tech stack**: Python (Pandas, NumPy), Data Visualization tools (Matplotlib / Seaborn), Machine Learning (e.g. Regression)  
- **Notebook**: `black_friday_sales_analysis.ipynb` containing code, visualizations, model training & evaluation  

---

## 📊 Key Findings

- Male customers contribute ~75% of transaction count. Males also spend more on average.  
- Among men, **single** men spend more than married ones.  
- Age group **25-40** shows the highest spending; younger or older age groups spend less.  
- Customers who have been in their city for 1 year tend to spend more; those who have lived >4 years spend less (possibly due to saturation or lower novelty).  

---

## 🔮 Predictive Modeling & Business Value

- Built a model (e.g. regression) that can forecast **purchase amount** based on customer & product attributes.  
- Using the model + insights, retail/eCommerce businesses can:  
  - Optimize pricing per product category  
  - Target marketing/demographic segments (e.g. single males, 25-40 age group)  
  - Adjust inventory / promotions during Black Friday to maximize revenue  

---

## 📂 Repository Structure

├── BlackFriday.csv # The raw dataset

├── black_friday_sales_analysis.ipynb # EDA + modeling notebook

└── README.md # Project description & findings
