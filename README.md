# 🛒 Dynamic Pricing Model for E-commerce

## 📌 Project Overview

This project focuses on developing a **dynamic pricing model** for e-commerce products using machine learning and Excel-based analysis. The goal is to predict the **optimal unit price** of products based on various factors such as demand, competitor pricing, and product metadata.

The solution demonstrates how dynamic pricing can improve decision-making by reducing pricing errors and increasing revenue potential.

---

## 🧠 Objective

- Predict **unit prices** of products based on:
  - Product demand
  - Competitor prices
  - Time-based features
  - Product characteristics
- Visualize trends and price accuracy using **Excel dashboards and charts**

---

## 📂 Dataset

**Source:** [Kaggle - Retail Price Optimization Dataset](https://www.kaggle.com/datasets/suddharshan/retail-price-optimization)

**Rows:** 676  
**Features:** 30 columns including:
- `qty`, `volume`, `customers` – demand indicators  
- `comp_1`, `comp_2`, `comp_3` – competitor prices  
- `freight_price`, `product_weight_g`, `product_photos_qty`  
- `month`, `holiday`, `weekend` – temporal context

---

## 🔧 Tools Used

| Component       | Technology             |
|----------------|-------------------------|
| Model           | Python (Scikit-learn – Linear Regression) |
| Data Handling   | Pandas, NumPy           |
| Visualization   | Microsoft Excel         |
| Output Format   | CSV, Excel Dashboards   |

---

## 🧪 Model Summary

- **Model Used:** Linear Regression
- **Evaluation Metrics:**
  - 🔢 **R² Score:** `0.99`
  - 📉 **Mean Squared Error (MSE):** `66.24`
- **Prediction Target:** `unit_price`

---

## 📈 Excel Visualizations

1. [**Category-wise Actual vs Predicted Price**](Visuals/Category-wise.png)
   - Clustered column chart showing pricing accuracy by product category
2. [**Month-wise Price Trends**](Visuals/Month-wise.png)
   - Line chart tracking actual vs predicted prices over months
3. [**Demand-based Pricing Analysis**](Visuals/Demand-wise.png)
   - Clustered column chart comparing prices at different volume ranges

---

## 📊 Insights

- The model accurately predicts unit prices across product types and time periods
- Minimal price deviation between predicted and actual values
- Demand levels significantly influence price behavior — higher volumes tend to correlate with slightly optimized pricing

---


**Humera Shaik**  


## 👩‍💻 About Me
Humera Shaik
📊 Data Analyst | 🎯 Forecasting & Insight Generation | 🤖 AI Automation | Python | Machine Learning | Excel | Power BI  

📧 Email: [humerah610@gmail.com](mailto:humerah610@gmail.com)

📱 Phone: +91 7382273550

🔗 [LinkedIn](https://www.linkedin.com/in/humera-shaik-dataanalyst/)
📄 [View My Resume](HS%20DA%2045.pdf)
