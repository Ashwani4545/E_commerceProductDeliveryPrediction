# 📦 E-Commerce Product Delivery Prediction

This project aims to predict whether a product from an international e-commerce company will be delivered on time. Alongside prediction, the project explores key logistical and customer-related factors influencing delivery success. The dataset comprises 10,999 entries and 12 features related to product shipment, customer behavior, and warehouse logistics.

## 🚀 Technologies Used
- Python, Pandas, Seaborn, Matplotlib
- Scikit-learn (Random Forest, Decision Tree, Logistic Regression, KNN)
- Jupyter Notebook

## 📊 Key Insights
- Product weight and cost significantly affect delivery success.
- Delays correlate with increased customer care calls.
- Loyal customers (those with prior purchases) experience higher on-time delivery rates.

## 🧠 ML Models Performance
| Model                | Accuracy |
|---------------------|----------|
| Decision Tree        | 69%      |
| Random Forest        | 68%      |
| Logistic Regression  | 63%      |
| K-Nearest Neighbors  | 65%      |

## 📌 Conclusion
Products with weights between **2500–3500 grams** and costing under **$250** were more likely to be delivered on time. Shipments from **Warehouse F** (likely near a port) were most common. Discounts above **10%** correlated with higher on-time deliveries. The **Decision Tree model** gave the best performance.
