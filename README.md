Project Title

Online Shopper Purchase Prediction

📖 Overview

This project uses machine learning to predict whether an online visitor will make a purchase based on session behavior.

The goal is to help businesses improve customer targeting, optimize marketing strategies, and increase conversion rates.

📊 Dataset
Rows: 12,330
Features: 18 → expanded to 27 after encoding
Target: Revenue (Purchase / No Purchase)
Missing Values: None
🔍 Key Insights
Dataset is imbalanced (84.5% non-buyers)
Buyers:
Spend more time on product pages
Have lower bounce and exit rates
Show significantly higher page values
⚙️ Technologies Used
Python
Pandas, NumPy
Matplotlib
Scikit-learn
🤖 Models Built
Model	Accuracy	Recall (Buyers)	Precision
Logistic Regression	87%	0.35	0.75
Logistic (Balanced)	86%	0.75	0.55
Random Forest	89%	0.53	0.74
🧠 Key Achievement

Improved buyer detection significantly:

Recall increased from 35% → 75% using class balancing
💼 Business Impact
Helps identify high-intent customers
Improves marketing targeting
Increases conversion efficiency
🚀 Future Improvements
XGBoost / LightGBM
Model explainability (SHAP)
Deployment with Streamlit
Real-time prediction system
📬 Author

zhitsu jiya

Data Scientist
Nigeria
