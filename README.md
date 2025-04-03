Telecom Customer Churn Prediction
📌 Project Overview
This project predicts whether a telecom customer will churn (leave the service) based on their usage patterns and demographics. By identifying key factors influencing churn, businesses can improve customer retention.

📂 Dataset
Includes customer details such as:

Demographics (Gender, Senior Citizen, etc.)

Account Info (Contract Type, Monthly Charges, Tenure)

Service Usage (Internet Service, Streaming, Tech Support)

Churn Label (Yes/No)

🛠️ Technologies & Libraries
Data Handling: Python, Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Machine Learning: Scikit-learn, XGBoost, Random Forest, Logistic Regression

Preprocessing: Label Encoding, Standard Scaling, Train-Test Split

Model Optimization: GridSearchCV

📊 Workflow
EDA & Preprocessing: Cleaned data, handled missing values, performed feature engineering.

Model Training: Trained Logistic Regression, Decision Tree, Random Forest, and XGBoost models.

Evaluation: Measured accuracy, precision, recall, F1-score to find the best-performing model.

Insights: Month-to-month contracts and high monthly charges increase churn risk.

💻 How to Use
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/telecom-churn-prediction.git
cd telecom-churn-prediction
Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
