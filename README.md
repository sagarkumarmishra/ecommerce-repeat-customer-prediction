

<p align="center">
  <img width="280" height="280" alt="bits" src="https://github.com/user-attachments/assets/29241428-204b-4527-879c-74d66524fef4" />
</p>













<h1 align="center">E-Commerce Repeat Customer Prediction</h1>

<p align="center">
  <b>Introduction to Data Science – Assignment 1</b><br>
  <b>Course:</b> S2-22_DSECLZG532 | <b>Group 9, Section 1</b><br>
  <b>Submitted by:</b> Sagar Kumar Mishra<br>
  <b>BITS Pilani Work Integrated Learning Programmes</b>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Python-3.9%2B-blue.svg"></a>
  <a href="#"><img src="https://img.shields.io/badge/Pandas-2.0%2B-green.svg"></a>
  <a href="#"><img src="https://img.shields.io/badge/Scikit--Learn-1.3-orange.svg"></a>
  <a href="#"><img src="https://img.shields.io/badge/Accuracy-100%25-brightgreen.svg"></a>
  <a href="#"><img src="https://img.shields.io/badge/License-MIT-yellow.svg"></a>
</p>

---

### Business Problem  
**Predict whether a customer will make repeat purchases** based on behavior to enable targeted marketing and improve customer retention for e-commerce stores.

### Dataset  
[Kaggle: E-commerce Customer Engagement](https://www.kaggle.com/datasets/noir1112/e-commerce-customer-engagement/data)  
- 10,000+ customers  
- 23 features: Age, TotalPurchases, CLV, Engagement Rates, Returns, etc.

### Key Results  
- **Random Forest achieved 100% Accuracy, Precision, Recall & F1-Score**  
- Removed 4,478 noisy rows & fixed negative Age/CLV values  
- Top 5 predictive features identified via **Mutual Information + Chi-Squared**

### CRISP-DM Methodology Followed  
1. Business Understanding  
2. Data Understanding & Exploration  
3. Data Preparation (Cleaning + Encoding)  
4. Feature Selection  
5. Modeling (Decision Tree + Random Forest)  
6. Evaluation & Comparison  
7. Conclusion & Business Insights  

### Model Performance  
| Model             | Accuracy | Weighted F1 | AUC-ROC |
|-------------------|----------|-------------|---------|
| Decision Tree      | 99%      | 0.99        | 0.98    |
| **Random Forest**  | **100%** | **1.00**    | **0.99** |

### Top 5 Features (Random Forest Importance)  



### Files in Repository  
- `IDS_Assignment-1.ipynb` → Complete Jupyter notebook with code, plots, explanations  
- `ecommerce_customer_data_cleaned.csv` → Cleaned dataset  
- `ecommerce_customer_data_encoded.csv` → ML-ready encoded version  
- `bits-pilani-logo.png` → Official BITS Pilani emblem (uploaded)

### Business Recommendation  
Deploy the **Random Forest model** in production to:  
- Score customers in real-time  
- Prioritize high-CLV & high-purchase users  
- Launch personalized loyalty campaigns  
- **Maximize repeat purchase rate and revenue**

### Visualizations Included  
- Correlation Heatmap  
- Scatter Plots vs Target  
- Bar, Pie, Line Charts  
- Confusion Matrices  
- ROC Curve Comparison  
