# 🎇 Diwali Sales Analysis & Customer Spending Prediction

## 📌 Project Overview
This project focuses on analyzing Diwali sales data to understand customer purchasing behavior and identify the key factors that influence festive spending. The project includes exploratory data analysis (EDA), data preprocessing, and the implementation of a supervised machine learning regression model to predict the amount spent by customers.

The goal of this project is to demonstrate an end-to-end data analytics workflow suitable for a Data Analyst role, combining business insights with basic machine learning.

---

## 🎯 Business Objective
- Analyze customer demographics, regions, and product categories to identify sales patterns during Diwali.
- Understand which customer segments contribute the most to revenue.
- Build a machine learning model to predict customer spending based on historical data.
- Provide insights that can help businesses improve festive sales strategies and customer targeting.

---

## 📊 Dataset Overview
- **Rows:** 11,239  
- **Columns:** 13  
- **Dataset Type:** Structured sales transaction data  
- **Target Variable:** Amount  

### Key Features
- Gender
- Age
- Age Group
- Marital Status
- State
- Zone
- Occupation
- Product Category
- Orders

---

## 🧹 Data Cleaning & Preprocessing
The following steps were performed to prepare the data:
- Removed irrelevant identifier columns such as User_ID and Customer Name.
- Handled missing values to ensure data consistency.
- Removed duplicate records.
- Converted categorical variables into numerical format using One-Hot Encoding.
- Split the dataset into training and testing sets (80% train, 20% test).

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights from EDA include:
- Female customers contribute more to overall Diwali sales compared to male customers.
- Customers aged **26–35** are the highest contributors in both sales amount and number of orders.
- A few states such as **Uttar Pradesh, Maharashtra, and Karnataka** generate a large portion of total revenue.
- Sales are highly concentrated in a few product categories, with **Food** and **Clothing & Apparel** dominating festive purchases.

These insights helped guide feature selection for the machine learning model.

---

## 🤖 Machine Learning Model
- **Model Used:** Linear Regression  
- **Problem Type:** Supervised Learning (Regression)  
- **Target Variable:** Amount  

### 📈 Model Evaluation
- **R² Score:** 0.64  
- **Mean Absolute Error (MAE):** ₹2,372  

**Interpretation:**
- The model explains approximately **64% of the variance** in customer spending behavior.
- On average, the predicted amount differs from the actual amount by around **₹2,372**, which is reasonable compared to typical Diwali order values.

---

## 🧩 Solution to Business Objective
- Identified high-value customer segments based on age, gender, and region.
- Highlighted top-performing states and product categories for festive sales.
- Built a regression model to estimate customer spending for better business planning.
- Provided data-driven insights that can support marketing and inventory decisions during festive seasons.

---

## ✅ Conclusion
- Customer spending during Diwali is strongly influenced by demographics, location, and product category.
- Middle-aged customers (26–35) and female customers play a major role in revenue generation.
- A small number of states and product categories drive most of the sales.
- The Linear Regression model provides reasonably accurate spending predictions.
- This project demonstrates a complete data analytics workflow, from raw data to business insights and machine learning.

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 👩‍💻 Author
**Anushree Kashyap**  
📧 Email: anushreekashyap03@gmail.com  

---

⭐ If you find this project useful, feel free to give it a star!
