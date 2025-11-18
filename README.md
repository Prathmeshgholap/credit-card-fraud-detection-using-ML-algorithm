# credit-card-fraud-detection-using-ML-algorithm
Credit Card Fraud Detection using Python, featuring data cleaning, feature engineering, SMOTE balancing, and ML model evaluation.
🛡️ Credit Card Fraud Detection

A Machine Learning project to classify fraudulent credit card transactions using Python.
The dataset is highly imbalanced, so techniques like SMOTE and Robust Scaling were applied to improve fraud detection performance.

📌 Project Overview

Built a fraud detection model using Logistic Regression, Random Forest, and Gradient Boosting.

Engineered features like transaction hour, transaction day, customer age, and location-based attributes.

Performed data cleaning, encoding, scaling, outlier handling, and model evaluation.

🛠️ Tech Stack

Python, Pandas, NumPy

Scikit-Learn, Imbalanced-Learn

Matplotlib, Seaborn

📂 Dataset Info

Rows: 555k+

Target Column: is_fraud

Fraud Cases: ~0.38% (highly imbalanced)

Features include amount, merchant, category, customer details, location, and transaction time.

🔍 Key Insights (EDA)

Fraud transactions usually involve higher transaction amounts.

Most demographic features (gender, age, city, population) show very low correlation with fraud.

Fraud is spread across multiple spending categories.

Amount is the strongest predictor of fraud.

🤖 Models Used

Logistic Regression (Tuned)

Random Forest Classifier

Gradient Boosting Classifier

📈 Model Performance
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	91%	3%	74%	6%
Random Forest	100%	57%	77%	65%
Gradient Boosting	96%	8%	83%	15%
🏆 Best Model
Random Forest Classifier

Best balance between detecting fraud & avoiding false alarms

Lowest false positives

Highest overall F1 score

Most reliable for real-world fraud detection

🔮 Future Scope

Use advanced models like XGBoost or CatBoost

Deploy the system using Flask/FastAPI

Add real-time monitoring & alerting

Combine multiple financial datasets for improved accuracy

👨‍💻 Author

Prathmesh Gholap
Data Analytics Student – I.T Vedant
Guided by Punit Kanojiya Si
