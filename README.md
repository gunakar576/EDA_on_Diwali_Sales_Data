# Retail-Sales-Data-Analysis-and-Customer-Insights

# 🛍️ Retail Sales Data Analysis and Customer Insights

## 📌 Overview
This project focuses on **Exploratory Data Analysis (EDA)** of retail sales data during a festive season.  
The goal was to analyze **customer demographics, product preferences, sales performance**, and provide **business insights** that can help improve marketing strategies, product targeting, and customer engagement.

---

## 📂 Dataset
The dataset contains:
- **Customer Demographics** (Gender, Age Group, Marital Status, Occupation, Zone, State)
- **Order Details** (Product ID, Product Category, Orders, Amount)
- **Transaction Information** (Total Purchase Amount, Average Purchase)

---

## 🔧 Data Preparation & Cleaning
- Removed **missing values** and **duplicates**
- Standardized **categorical variables** (Gender, Age Group, Zones, Marital Status)
- Converted date & numerical columns into correct formats
- Created derived features:
  - **Age Groups**
  - **Revenue contribution**
  - **Average Purchase Amount**

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- **Gender**: Females placed more orders (19,554) and spent ₹74.3M, compared to males (8,427 orders, ₹31.8M).
- **Age Group**: 26–35 age group was the top contributor (11,381 orders, ₹42.6M).
- **Marital Status**: Unmarried customers purchased more (16,243 orders, ₹62.1M).
- **Zone**: Central Zone dominated (10,636 orders, ₹41.6M).
- **Top Customers & Products**: Identified top 10 revenue-generating customers and products.

### 🔹 Bivariate Analysis
- **Gender vs Product Category**: Clothing & Apparel, Food, and Electronics were most popular.
- **Age Group vs Product Category**: 26–35 age group purchased the most across categories.
- **Marital Status vs Orders & Revenue**: Unmarried customers spent more than married.
- **Zone vs Revenue**: Central Zone (Uttar Pradesh, Delhi) contributed the most.
- **Occupation vs Purchases**: IT and Healthcare professionals were the biggest contributors.

### 🔹 Multivariate Analysis
- **Age Group + Gender**: Females (26–35) contributed the highest revenue (₹30.9M).
- **State + Zone**: Uttar Pradesh (Central) and Maharashtra (Western) were top-performing states.
- **Product Category + Orders + Revenue**:
  - Clothing & Apparel → Highest purchase frequency
  - Electronics & Footwear → High revenue contribution

---

## 💡 Key Insights
- Female customers aged **26–35** are the **most valuable segment**.
- **Unmarried customers** purchase more frequently and spend more.
- **Central Zone** is the strongest revenue region (esp. Uttar Pradesh).
- **Clothing & Apparel** is most popular, while **Electronics & Footwear** drive high revenue.
- Marketing campaigns should target **young, unmarried females (26–35)** in Central & Western India.

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Matplotlib & Seaborn** (Data Visualization)
- **EDA Techniques** (Univariate, Bivariate, Multivariate)
- **Statistical Aggregations** (Orders, Revenue, Average Amount)

---

## 📈 Business Impact
- Helped identify **customer segments with the highest value**.
- Showed which **product categories** drive revenue.
- Provided **regional insights** for targeted marketing.
- Demonstrated the importance of **data storytelling in decision-making**.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/retail-sales-analysis.git
